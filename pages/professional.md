---
layout: page
show_meta: false
title: "Professional Journey"
subheadline: "My career trajectory"
header:
   image_fullwidth: "header_professional.jpg"
permalink: "/professional/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>