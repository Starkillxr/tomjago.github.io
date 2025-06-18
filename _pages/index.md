---
layout: default
filename: index.md
published: false
---
<ul>
  {% for post in site.posts %}
    <li>
      <a>{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>