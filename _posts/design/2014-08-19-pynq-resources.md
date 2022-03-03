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

PYNQ has been widely used for machine learning research and prototyping.

FINN, an experimental framework from Xilinx Research Labs to explore deep neural network inference on FPGAs. It specifically targets quantized neural networks, with emphasis on generating dataflow-style architectures customized for each network. 

FINN makes extensive use of PYNQ as a prototyping platform. 

For more information see <a href="https://xilinx.github.io/finn/">xilinx.github.io/finn</a>

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
