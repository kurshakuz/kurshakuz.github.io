---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#

layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "About me"
  url: 'http://kurshakuz.github.io/info/'
  image: me1.jpg
  text: 'Here is some information about my background, education, skills, and experiences. If you like to know more, feel free to contact me, all information is available here too.'
widget2:
  title: "Portfolio"
  url: 'http://kurshakuz.github.io/portfolio/'
  image: widget-1-302x182.jpg
  text: 'Here is all projects that I have done during my studies, research work or out of willingnes. My interest span from mobile robotics and control to computer vision and deep learning'

widget3:
  title: "Blog"
  url: 'http://kurshakuz.github.io/blog/'
  image: widget3.jpg
  text: 'Here I share my thoughts about my hobbies, education, and work. It consists of various topics starting from mountain hiking, snowboarding, active tourism to career in robotics and mechatronics and graduate schools'
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
  url: http://kurshakuz.github.io/contact
  text: Contact me ›
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
