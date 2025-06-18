---
layout: page
filename: index.md
--- 

<body>
    {% for post in site.posts %}
        <h1>{{ post.title }}</h1>
        <time datetime="{{post.date}}">
        {{post.excerpt}}
    {% endfor %}
</body>
---