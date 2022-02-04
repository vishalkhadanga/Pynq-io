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
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: PYNQ.JPG
  text: '<em>PYNQ</em> has a small but growing range of boards that enable designers to exploit the benefits of programmable logic and microprocessors to build more capable and exciting electronic systems. They can be used with Xilinx ZYNQ products.'
widget2:
  title: "PYNQ Community"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: 'The <em>PYNQ Community</em> is a collection of project tutorials, training videos and other resources to help you get the most out of your PYNQ board. <br/>1. <a href="#">PYNQ Embedded community projects</a><br/>2. <a href="#">PYNQ Alveo community projects and tutorials</a><br/>3.<a href="#">Machine Learning on Xilinx FPGAs with FINN</a>.<br/>4.<a href="#">Tutorials and other resources.</a><br/>5.<a href="#">Example Notebooks.</a><br/>5.
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Download Theme"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. The code is well-documented and explains you how it works.'
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
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
