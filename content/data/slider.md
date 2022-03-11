---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
  - title: Energy Watch
    content: xxx
    align: center
    background:
      position: right
      color: '#666'
      brightness: 0.7
      media: energy.jpg
  - title: Basin Explorer
    content: xxx
    align: left
    background:
      position: center
      color: '#555'
      brightness: 0.7
      media: river.jpg
    link:
      icon: browser
      icon_pack: fas
      text: Join Us
      url: ../contact/
---
