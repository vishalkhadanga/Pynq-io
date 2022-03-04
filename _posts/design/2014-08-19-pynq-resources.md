---
layout: page-fullwidth
title:  "Other PYNQ Resources"
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
# PYNQ Alveo community porjects and tutorials

PYNQ can be used with <a href="https://www.xilinx.com/products/boards-and-kits/alveo.html">Alveo accelerator boards</a> and <a href="https://aws.amazon.com/ec2/instance-types/f1/">AWS-F1</a>. The following examples can be installed on the host computer and run on the Alveo board or on an AWS-F1 instance. 

<div class="row t60">

{% for item in site.data.pynqprojalveo.docs %}
    <div class="medium-3 columns">
        <div class="imgcont"><center><img src="{{ site.urlimg }}{{ item.img }}"></center></div>
        <center><p><a href="{{ item.url }}"><h5>{{ item.project }}</h5></a></p></center>
    </div><!-- /.medium-6.columns -->
{% endfor %}
</div><!-- /.row -->


# Machine Learning on Xilinx FPGAs with FINN

<p> <a href="https://phlow.github.io/feeling-responsive/design/mediaelement_js/" title="Play Audio &amp; Video with media&shy;element.js"><img src="https://phlow.github.io/feeling-responsive/images/mediaplayer_js-thumb.jpg" class="alignleft" width="150" height="150" alt="Blog of Feeling Responsive"></a> Do you like music? Or are you a podcaster? Do you want to stream your videos in a nice player? Than you likely will like the integration of mediaelement.js. It enables you to play music and stream video in a consistent player that looks in each browser delicious. It even works in IE6-8. <a href="https://phlow.github.io/feeling-responsive/design/mediaelement_js/" title="Read Play Audio &amp; Video with media&shy;element.js"><strong>Read More&nbsp;›</strong></a></p>



# Tutorials and Other Resources

<div class="row t60">

{% for item in site.data.pynqtut.docs %}
    <div class="medium-3 columns">
        <div class="imgcont"><center><img src="{{ site.urlimg }}{{ item.img }}"></center></div>
        <center><p><h5>{{ item.subtitle }}<a href="{{ item.url }}">{{ item.project }}</a></h5></p></center>
    </div><!-- /.medium-3.columns -->
{% endfor %}
</div><!-- /.row -->


# Example Notebooks

A selection of notebook examples are shown below that are included in the PYNQ image. The notebooks contain live code, and generated output from the code can be saved in the notebook. Notebooks can be viewed as webpages, or opened on a Pynq enabled board where the code cells in a notebook can be executed. 

<div class="row t60">

{% for item in site.data.exnote.docs %}
    <div class="medium-3 columns">
        <div class="imgcont"><center><img src="{{ site.urlimg }}{{ item.img }}"></center></div>
        <center><p><h5><a href="{{ item.url }}">{{ item.project }}</a></h5></p></center>
    </div><!-- /.medium-3.columns -->
{% endfor %}
</div><!-- /.row -->
