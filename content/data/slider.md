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
    content: The Energy Watch visualises electricity assets across Israel, Palestine and Jordan. It takes a transboundary systems perspective to understand regional trends, as well as identify opportunities for cross-border collaboration.
    align: left
    background:
      position: right
      color: '#666'
      brightness: 0.4
      media: solar.jpg
    link:
      icon: fa-browser
      icon_pack: fas
      text: Launch Platform
      url: https://gcp-europe-west1.app.carto.com/map/cacf8f5f-9e42-4130-a0b6-7b2b0c2928e9
  #
  - title: Water Resource Watch
    content: Monitoring the usage of critical freshwater and wastewater resources across Israel, Palestine and Jordan. Taking a transboundary approach to map pathways to a more sustainable water system.
    align: left
    background:
      position: center
      color: '#555'
      brightness: 0.4
      media: river.jpg
    link:
      icon: fa-browser
      icon_pack: fas
      text: Launch Platform
      url: https://gcp-europe-west1.app.carto.com/map/21f9a73c-3573-4374-83fd-9517ac4476d2
  #
  - title: Population Watch
    content: Monitoring the pulse of social trends in the Israel, Palestine and Jordan region.
    align: left
    background:
      position: center
      color: '#555'
      brightness: 0.4
      media: population.jpeg
    link:
      icon: fa-browser
      icon_pack: fas
      text: Launch Platform
      url: https://gcp-europe-west1.app.carto.com/map/93b92f69-25ec-4204-b759-3c4c5843ee15
---
