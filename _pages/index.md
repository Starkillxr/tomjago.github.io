'''markdown
--
layout: page
filename: index.md
published: false
---
{% for post in site.posts %}
    <h2>{{ post.title }}</h2>
    <p class="excerpt">{{ post.excerpt}} </p>
{% endfor %}
'''