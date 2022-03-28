---
layout              : page-fullwidth
show_meta           : false
title               : "PYNQ Boards"
subheadline         : 
teaser              : 
header:
   image_fullwidth  : "Topimage.jpg"
permalink           : "/boards/"
---

See our collection of PYNQ and PYNQ compatible boards!

<div class="row">
{% for item in site.data.boards.docs %}
<div class="column">
  <div class="card" padding-bottom="20px">
    <img class="cardimg" src="{{ site.urlimg }}{{ item.img }}" alt="{{ item.board }}">
    <h1>{{ item.board }}</h1>
    <p class="price">{{ item.subhead }}</p>
    <p>{{ item.info }}</p>
    <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
  </div>
</div>
{% endfor %}
</div>