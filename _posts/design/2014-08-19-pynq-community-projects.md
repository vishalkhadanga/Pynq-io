---
layout: page-fullwidth
title:  "PYNQ Community Projects"
subheadline:
teaser: 
categories:
    - design
header:
   image_fullwidth: header_unsplash_leaf.jpg
---
The PYNQ embedded community page highlights examples of projects for Zynq based boards.

Examples include image and video processing, robot and industrial control, machine learning, RISC-V prototyping, RFSoC QPSK and more. 

<!--more-->


<div class="row t60">

{% for item in site.data.pynqcommunity.docs %}
    <div class="medium-3 columns">
        <div class="imgcont"><center><img src="{{ site.urlimg }}{{ item.img }}"></center></div>
        <center><p><h5>{{ item.college }}: </h5><a href="{{ item.url }}">{{ item.project }}</a></p></center>
    </div><!-- /.medium-6.columns -->
{% endfor %}
</div><!-- /.row -->


<div class="pagination">
  <a href="#">&laquo;</a>
  <a class="active" href="/design/pynq-community-projects/">1</a>
  <a href="#">2</a>
  <a href="#">&raquo;</a>
</div>



