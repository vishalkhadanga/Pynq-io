---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: Topimage.jpg
widget1:
  title: "PYNQ Board Portfolio"
  url: 'http://zacarhay.github.io/feeling-responsive/blog/'
  image: pynqimg.png
  text: '<em>PYNQ</em> has a small but growing range of boards that enable designers to exploit the benefits of programmable logic and microprocessors to build more capable and exciting electronic systems. They can be used with Xilinx ZYNQ products.'
widget2:
  title: "PYNQ Community"
  url: 'http://zacarhay.github.io/feeling-responsive/headers/'
  image: community.png
  text: 'The <em>PYNQ Community</em> is a collection of project tutorials, training videos and other resources to help you get the most out of your PYNQ board. <br/>1. <a href="#">PYNQ Embedded community projects</a><br/>2. <a href="#">PYNQ Alveo community projects and tutorials</a><br/>3.<a href="#">Machine Learning on Xilinx FPGAs with FINN</a>.<br/>4.<a href="#">Tutorials and other resources.</a><br/>5.<a href="#">Example Notebooks.</a>'
widget3:
  title: "Getting Started"
  url: 'http://zacarhay.github.io/feeling-responsive/getting-started/'
  image: setup.png
  text: 'You need a supported Xilinx platform to get started. How you get PYNQ depends on your platform. For some Zynq|Zynq Ultrascale+ platforms you can download an SD card image to boot the board. For other platforms, including Alveo, you can install PYNQ onto your host Operating System.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

