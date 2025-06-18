---
layout: page
filename: index.md
---


<hr>
<h1> Blog Posts </h1>
<ul>
   {% for post in site.posts %}
    <pre>
       <h3 style ="margin = 0px; padding =0px;">{{ post.title }}</h3>
       <p style="color:#808080; margin = 0px; padding = 0px"><time datetime="{{ post.date | date: '%Y-%m-%d %H:%M' }}">{{ post.date | date: "%B %-d, %Y %I:%M %p"}}</time></p>
    </pre>
       <p>{{post.excerpt}}</p>
   {% endfor %}
</ul>
