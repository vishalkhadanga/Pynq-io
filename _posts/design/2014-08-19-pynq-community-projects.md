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

<div class="w3-row">

    {% for item in site.data.pynqcommunity.docs %}
    <div class="w3-col s4 w3-green w3-center">
        <center><img src="{{ site.urlimg }}{{ item.img }}"></center>
        <center><p><h5>{{ item.college }}: </h5><a href="{{ item.url }}">{{ item.project }}</a></p></center>
    </div><!-- /.medium-3.columns -->
    {% endfor %}
    
</div><!-- /.row -->






