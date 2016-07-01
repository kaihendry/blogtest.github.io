---
title: Blogging Like a Pro
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date_to_long_string }} &dash; {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
