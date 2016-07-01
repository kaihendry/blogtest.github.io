---
title: Blogging Like a Pro
---
<p><a href=https://github.com/kaihendry/kaihendry.github.io/new/master/_posts">Create new blog</a></p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date_to_long_string }} &dash; {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
