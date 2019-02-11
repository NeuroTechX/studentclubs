---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header: no

widget1:
  title: "Clubs"
  url: '/clubs/'
  image: clubs-thumb.jpg
  text: 'Learn about the Student Clubs currently involved with NeuroTechX.'
  
widget2:
  title: "Competition"
  url: '/competition/'
  image: competition-thumb.JPG
  text: 'Discover the two challenges of the NTX competition 2019.'

widget3:
  title: "Get Started"
  url: '/get-started/'
  image: getstarted-thumb.jpg
  text: 'Get on the right track toward making your own Student Club.'

widget4:
  title: "Curriculum"
  url: '/curriculum/'
  image: curriculum-thumb.JPG
  text: 'What do a new student clubs should focus on?'

widget5:
  title: "FAQ"
  url: '/FAQ/'
  image: faq-thumb.jpg
  text: 'See here for a list of Frequently Asked Questions.'

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
  url: http://eepurl.com/bEQDKX
  text: Subscribe to the NeuroTechX newsletter ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

# NeuroTechX Student Clubs

Neurotechnology has never been this accessible before. We want to catalyze the interest and involvement of skilled students by providing them with a precise goal to work towards and the resources to get there.

The NeuroTechX Student Club Competition promotes interdisciplinary collaboration, preparing the participants for careers and excellence in science, technology, engineering and mathematics (STEM) through self-learning, knowledge sharing, and practical experimentation.

We believe neurotechnology is key to better understanding and to improving who we are. We aim to inspire a whole new generation of neuroengineers, who will be equipped to drive the field forward.

[![NTX SC Competition 2019]({{ site.url }}{{ site.baseurl }}/images/NTXSC-Comp2019.png "NeuroTechX Student Clubs Competition # 2019")]({{ site.url }}{{ site.baseurl }}/competition)

#
# [![NTX SC Competition 2018]({{ site.url }}{{ site.baseurl }}/images/NTXSC2018_Flyer.png "NeuroTechX Student Clubs Competition # 2018")]({{ site.url }}{{ site.baseurl }}/competition)
#