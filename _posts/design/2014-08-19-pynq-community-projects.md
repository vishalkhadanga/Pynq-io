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
## Liquid 

<div class="row t60">
    {% for item in site.data.pynqcommunity.docs %}
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}{{ item.img }}"></center>
        <p><h3>{{ item.college }}: </h3><a href="{{ item.url }}">{{ item.project }}</a></p>
    </div><!-- /.medium-6.columns -->
    {% endfor %}
</div><!-- /.row -->







<div class="row t60">

    <div class="medium-3 columns">
        <center><img src="{{ item.urlimg }}gal2.jpg" alt=""></center>
        <p>Politechnico di Milano: <a href="https://bitbucket.org/necst/xohw2020_plaster_public">PYNQ Plaster - Abandoned object detection using map-reduce on multi-FPGA cluster</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal3.jpg" alt=""></center>
        <p>University of Zaragoza: <a href="https://github.com/eneriz-daniel/sensorialfusionQNNs">Sensorial fusion via QNNs</a></p>
    </div><!-- /.medium-6.columns -->

        <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal8.jpg" alt=""></center>
        <p>Strathclyde University: <a href="https://github.com/smpis/PyPix">Pypix - 3D scene reconstruction based on stereo vision</a></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal4.gif" alt=""></center>
        <p>Fred Kellerman: <a href="https://github.com/FredKellerman/pynq-juliabrot">PYNQ fractal factory</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal5.png" alt=""></center>
        <p>XUP China Summer School: <a href="https://github.com/XilinxCannonFodderTeam/smart_lock">PYNQ Smart Lock</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal6.png" alt=""></center>
        <p>XUP China Summer School: <a href="https://github.com/PaiPai121/Defocus-Image-Deblurring-Based-on-PYNQ">Defocus Image Deblurring</a></p>
    </div><!-- /.medium-6.columns -->

        <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal7.jpg" alt=""></center>
        <p>XUP China Summer School: <a href="https://github.com/Microdent/Handwritten_Mathematical_Calculator_on_FPGA">Handwritten Mechanical Calculator</a></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal9.png" alt=""></center>
        <p>XUP China Summer School: <a href="https://github.com/ZhangYuQAQ/Hardware-Acceleration-Circuit-Design-of-Object-Detection-Network-Based-on-FPGA">iSmart2 PYNQ Hardware </a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal10.png" alt=""></center>
        <p>XUP China Summer School: <a href="https://github.com/WilliamsCeng/02Hero">AES Encryption/Decryption</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal11.png" alt=""></center>
        <p>Southeast University, China; Xilinx China: <a href="https://github.com/Siudya/ORB_FPGA">PYNQ ORB feature extractor</a></p>
    </div><!-- /.medium-6.columns -->

        <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal12.gif" alt=""></center>
        <p>PYNQ gesture recognition: <a href="https://github.com/linxiaobo110/rps_u96">University of Science and Technology Beijing, Xilinx China</a></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal13.png" alt=""></center>
        <p>Xilinx University Program: <a href="https://github.com/xupsh/pynq-respeaker">PYNQ respeaker</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal14.png" alt=""></center>
        <p>Xilinx University Program China: <a href="https://github.com/xupsh/Pynq-CV-OV5640">PYNQ CV OV5640</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal15.png" alt=""></center>
        <p>Xilinx University Program China: <a href="https://github.com/xupsh/pynq-sense-hat">PYNQ Sense Hat</a></p>
    </div><!-- /.medium-6.columns -->

        <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal16.png" alt=""></center>
        <p>Jiangnan University, China: <a href="https://github.com/OpenHEC/SNN-simulator-on-PYNQcluster">SNN Simulator on PYNQ Cluster</a></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal17.png" alt=""></center>
        <p>Southeast University, China: <a href="https://github.com/Springbone/CC-Cam">CC-Cam a PYNQ diffuser camera</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal18.gif" alt=""></center>
        <p>University of Strathclyde: <a href="https://github.com/strath-sdr/rfsoc_sam">Open Source RFSoC Spectrum Analyzer</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal19.gif" alt=""></center>
        <p>Mahan Bastani, Nolan Chang, Atsushi Domyo, Daniel Kizito: <a href="https://github.com/Reconfigurable-Computing-CalPoly-Pomona/Motion-Controller">PYNQ S-Curve motion controller</a></p>
    </div><!-- /.medium-6.columns -->

        <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal20.png" alt=""></center>
        <p>Julian Bartolone: <a href="https://www.hackster.io/julian-bartolone2/ultra96-facial-recognition-deadbolt-using-pynq-0fe8e9">Ultra96 Facial Recognition Deadbolt Using PYNQ</a></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal21.gif" alt=""></center>
        <p>Adam Taylor: <a href="https://www.hackster.io/adam-taylor/pynq-controlled-neopixel-led-cube-92a1c1">PYNQ Controlled NeoPixel LED Cube</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal22.png" alt=""></center>
        <p>Giorgos Tzanos: <a href="https://github.com/AcceleratedCloud/SDSoC/tree/master/Gaussian%20NaiveBayes">Gaussian Naive Bayes NTUA</a></p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal23.gif" alt=""></center>
        <p>Rajeev Patwari, Nathalie Chan, King Choy: <a href="https://www.hackster.io/rajeev-patwari-ultra96-2019/ultra96-fpga-accelerated-parallel-n-particle-gravity-sim-87f45e">N-Particle Gravity Simulation on Ultra96</a></p>
    </div><!-- /.medium-6.columns -->

        <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}gal24.png" alt=""></center>
        <p>University Strathclyde: <a href="https://github.com/strath-sdr/rfsoc_qpsk">PYNQ RFSoC - QPSK demo on ZCU111</a></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->