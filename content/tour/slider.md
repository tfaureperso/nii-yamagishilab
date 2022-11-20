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
    - title: 👋 Welcome to the Yamagishi's Lab
      # content: Take a look at what we're working on...
      align: center
      background:
        position: left
        color: '#666'
        brightness: 0.7
        media: lab_kyoto.jpg
    # - title: Lunch & Learn ☕️
    #   content: 'Share your knowledge with the group and explore exciting new topics together!'
    #   align: left
    #   background:
    #     position: center
    #     color: '#555'
    #     brightness: 0.7
    #     media: contact.jpg
    - title: 'We are recruiting postdoctoral researchers!'
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: nii.png
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
