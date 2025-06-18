---
layout: page
filename: index.md
--- 

<ul>
    {% for post in site.posts %}
        {{ post.title }}
        {{ post.date }}
        {{post.excerpt}}
    {% endfor %}
</ul>
---