---
layout: page
permalink: /blog

title: "Блог"
header_title: "Блог"
---

В свободное от работы время я увлекаюсь написанием статей на самые различные
темы, которые меня интересуют. На этой странице собраны все публикации,
когда-либо написанные мной.

{% for post in site.categories.blog %}
[{{ post.date | date: "%-d-%m-%Y" }} {{ post.title }}]({{ post.url }})
{% endfor %}
