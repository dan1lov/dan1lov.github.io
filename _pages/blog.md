---
layout: page
permalink: /blog

title: "Блог"
header_title: "Блог"
---

Время от времени я публикую статьи разные темы, которые меня интересуют.
На этой странице собраны все публикации, когда-либо написанные мной.

{% for post in site.posts %}
[{{ post.date | date: "%-d-%m-%Y" }} {{ post.title }}]({{ post.url }})
{% endfor %}
