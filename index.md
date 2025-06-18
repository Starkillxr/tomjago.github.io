---
layout: page
filename: index.md
---
<ul>
  {% for post in site.posts %}
    <li>
      <h1>{{ post.title }}</h1>
      <h2>{{ post.excerpt }}</h2>
    </li>
  {% endfor %}
</ul>