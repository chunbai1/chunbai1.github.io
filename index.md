---

layout: default

title: My Blog

---

{% for post in site.posts %}

{{ post.title }}
{{ post.date }}

{% endfor %}