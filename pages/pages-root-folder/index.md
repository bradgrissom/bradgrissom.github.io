---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: jeff_splash_main.jpg
widget1:
  title: "Big game in Alaska"
  url: '/alaska/'
  image: alaska_widget_1_302x182.jpg
  text: 'Book hunts in Wrangell mountains and Adak'
widget2:
  title: "Big game in Colorado"
  url: '/colorado/'
  image: colorado_widget_1_302x182.jpg
  text: 'Elk, mule deer, antelope, and turkey all over Colorado'
widget3:
  title: "Big game in Washington"
  url: '/washington/'
  image: washington_widget_1_302x182.jpg
  text: 'White-tailed deer, black bear, and turkey in Northeast Washington'
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

# BAG Orig:
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
