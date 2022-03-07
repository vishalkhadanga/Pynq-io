---
layout              : page-fullwidth
show_meta           : false
title               : "PYNQ Boards"
subheadline         : 
teaser              : 
header:
   image_fullwidth  : "header_homepage_13.jpg"
permalink           : "/boards/"
---

See our collection of PYNQ and PYNQ compatible boards!

{% for item in site.data.boards.docs %}
<div class="card">
  <img src="{{ site.urlimg }}{{ item.img }}" alt="{{ item.alt }}" style="width:100%">
  <h1>{{ item.board }}</h1>
  <p class="price">{{ item.subhead }}</p>
  <p>{{ item.info }}</p>
  <p><button src="{{ item.url }}">See Vendor Website</button></p>
</div>
{% endfor %}
