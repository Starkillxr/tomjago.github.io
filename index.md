---
layout: page
filename: index.md
--- 

---
{% for post in site.posts %}
    <h1>{{ post.title }}</h1>
    <p> {{post.date}} </p>
    {{post.excerpt}}
{% endfor %}
---