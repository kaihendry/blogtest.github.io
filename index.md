---
title: Blogging Like a Pro
---

[Create new blog](https://github.com/kaihendry/kaihendry.github.io/new/master/_posts)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date_to_long_string }} &dash; {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
