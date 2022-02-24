---
layout: page
subheadline: "Header"
title: "PYNQ Community"
teaser: "See either of the links below:
    - PYNQ Community Projects: This Page shows the Embedded PYNQ Community Projects with tutorials on how to do them yourself!"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/pynq-community/"
---
<ul>
    {% for post in site.tags.pynq %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>