---
layout: page
filename: index.md
---


<hr>
<h1> Blog Posts <h1>
<ul>
   {% for post in site.posts %}
       <h2><b>{{ post.title }}</b></h2>
       <p style="color:#808080"><time datetime="{{ post.date | date: '%Y-%m-%d %H:%M' }}">{{ post.date | date: "%B %-d, %Y %I:%M %p"}}</time></p>
       {{post.excerpt}}
   {% endfor %}
</ul>

---