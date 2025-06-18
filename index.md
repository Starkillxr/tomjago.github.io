---
layout: page
filename: index.md
---
test 
---
<ul>
   {% for post in site.posts %}
       <h1><b>{{ post.title }}</b></h1>
       <p style="color:#808080"><time datetime="{{ post.date | date: '%Y-%m-%d %H:%M' }}">{{ post.date | date: "%B %-d, %Y %I:%M %p"}}</time></p>
       {{post.excerpt}}
   {% endfor %}
</ul>

---