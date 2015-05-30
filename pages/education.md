---
layout: page
show_meta: false
title: "한기대에서 알뜰하게 공부하기!"
subheadline: "Let's study more efficiently"
header:
   image_fullwidth: "education.jpg"
permalink: "/education/"
---
<ul>
    {% for post in site.categories.education %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>


