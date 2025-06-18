---
layout: page
filename: index.md
published: false
---

## Blog
{% for post in site._posts %}
    <h2>{{post.title}}</h2>
    <p class="excerpt">{{post.excerpt}}</p>
{% endfor %}