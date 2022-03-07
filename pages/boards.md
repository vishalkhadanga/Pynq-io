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

<div class="row t60">
{% for item in site.data.boards.docs %}
<div class="medium-3 columns">
<div class="card">
  <img src="{{ site.urlimg }}{{ item.img }}" alt="{{ item.board }}" style="width:100%">
  <h1>{{ item.board }}</h1>
  <p class="price">{{ item.subhead }}</p>
  <p>{{ item.info }}</p>
  <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
</div>
</div>
{% endfor %}
</div>
