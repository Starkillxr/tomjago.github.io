---
layout: page
filename: index.md
--- 

<ul>
    {% for post in site.posts %}
        <title>{{ post.title }}</title>
        {{ post.date }}
        {{post.excerpt}}
    {% endfor %}
</ul>
---