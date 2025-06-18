---
layout: page
filename: index.md
--- 

<ul>
    {% for post in site.posts %}
        <!-- <h1><b>{{ post.title }}</b></h1> -->
        <time datetime="{{ post.date }}">
        {{post.excerpt}}
    {% endfor %}
</ul>
---