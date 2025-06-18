---
layout: page
filename: index.md
---


<hr>
<h1 style="font-size:50px"> Blog Posts </h1>
<ul>
    {% for post in site.posts %}
        <header>
            <h3 style ="margin:0px; padding:0px;">{{ post.title }}</h3>
            <p style="color:#808080; margin:0px; padding:0px"><time datetime="{{ post.date | date: '%Y-%m-%d %H:%M' }}">{{ post.date | date: "%B %-d, %Y %I:%M %p"}}</time></p>
        </header>
        <hr>
        <p>{{post.excerpt}}</p>
    {% endfor %}
</ul>
