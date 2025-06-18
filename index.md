---
layout: page
filename: index.md
--- 

<ul>
    {% for post in site.posts %}
        <!-- <h1><b>{{ post.title }}</b></h1> -->
        <p><time datetime="{{ post.date }}"></time></p>
        {{post.excerpt}}
    {% endfor %}
</ul>
---