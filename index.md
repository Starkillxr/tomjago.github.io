---
layout: page
filename: index.md
--- 
<ul>
  {% for post in site.posts %}
      <h1>{{ post.title }}</h1>
      <p> {{post.date}} </p>
      <h2>{{ post.excerpt }}</h2>
  {% endfor %}
</ul>