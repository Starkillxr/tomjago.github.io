---
layout: page
filename: index.md
excerpt_seperator: <!-- excerpt-end -->
--- 
<ul>
  {% for post in site.posts %}
      <h1>{{ post.title }}</h1>
      <p> {{post.date}}
      <h2>{{ post.excerpt }}</h2>
  {% endfor %}
</ul>