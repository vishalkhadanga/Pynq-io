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
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr1.png" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ_Workshop">PYNQ Tutorial workshop</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr2.png" alt=""></center>
        <center><p>FPGA Developer: <a href="http://www.fpgadeveloper.com/2018/03/create-a-custom-pynq-overlay-for-pynq-z1.html">HLS filter example</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr3.png" alt=""></center>
        <center><p>Dustin Richmond: <a href="https://github.com/drichmond/PYNQ-HLS">PYNQ HLS Tutorial</a></p></center>
    </div><!-- /.medium-6.columns -->

        <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr4.png" alt=""></center>
        <center><p>FPGA Developer: <a href="http://www.fpgadeveloper.com/2018/03/how-to-accelerate-a-python-function-with-pynq.html">Accelerate FIR function</a></p></center>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr5.png" alt=""></center>
        <center><p>Video: <a href="https://www.youtube.com/watch?v=UBsCNPWudww">Control custom IP using GPIO</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr6.png" alt=""></center>
        <center><p>Video: <a href="https://www.youtube.com/watch?v=LomArt-hi4M">Add existing IP to a PYNQ overlay</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr7.png" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ_RFSOC_Workshop">PYNQ RFSoC tutorial workshop</a></p></center>
    </div><!-- /.medium-6.columns -->

        <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr8.png" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ_Bootcamp/">PYNQ bootcamp (High school level)</a></p></center>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr9.png" alt=""></center>
        <center><p><a href="https://github.com/MakarenaLabs/Xilinx-FPGA-HLS-PYNQ-ALVEO-Flow">Zynq, and Alveo video tutorials for PYNQ</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}tr10.png" alt=""></center>
        <center><p>Ryan Kastner, UCSD: <a href="https://pp4fpgas.readthedocs.io/">Parallel Programming for FPGAs: PYNQ Projects and Labs</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="" alt=""></center>
        <center><p><a href=""></a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="" alt=""></center>
        <center><p><a href=""></a></p></center>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


# Example Notebooks

A selection of notebook examples are shown below that are included in the PYNQ image. The notebooks contain live code, and generated output from the code can be saved in the notebook. Notebooks can be viewed as webpages, or opened on a Pynq enabled board where the code cells in a notebook can be executed. 

<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n1.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/boards/Pynq-Z1/base/notebooks/pmod/pmod_adc.ipynb">ADC Waveforms</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n2.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/boards/Pynq-Z1/base/notebooks/pmod/pmod_dac_adc.ipynb">DAC ADC Example</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n3.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/pynq/notebooks/common/overlay_download.ipynb">Downloading Overlays</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n4.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/boards/Pynq-Z1/base/notebooks/pmod/pmod_grove_adc.ipynb">Grove ADC</a></p></center>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n5.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/tree/v1.4/Pynq-Z1/notebooks/examples/arduino_analog.ipynb">Arduino Analog Example</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n6.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/tree/v1.4/Pynq-Z1/notebooks/examples/opencv_filters_webcam.ipynb">OpenCV Software Filters</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n7.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/boards/Pynq-Z1/base/notebooks/arduino/arduino_grove_ledbar.ipynb">Grove LED Bar</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n8.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/boards/Pynq-Z1/base/notebooks/video/opencv_face_detect_hdmi.ipynb">OpenCV Face Detection</a></p></center>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n9.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/boards/Pynq-Z1/base/notebooks/audio/audio_playback.ipynb">PYNQ Audio</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n10.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/pynq/notebooks/common/usb_webcam.ipynb">USB Webcam</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n11.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/boards/Pynq-Z1/base/notebooks/pmod/pmod_grove_tmp.ipynb">Shell Commands</a></p></center>
    </div><!-- /.medium-6.columns -->

    <div class="medium-3 columns">
        <center><img src="{{ site.urlimg }}n12.jpg" alt=""></center>
        <center><p><a href="https://github.com/Xilinx/PYNQ/blob/v2.0/pynq/notebooks/common/usb_wifi.ipynb">USB Wifi</a></p></center>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->