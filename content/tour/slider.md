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
    - title: 👋 Welcome to the BSA UNR Website
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: featured.jpg
    - title: Event & Get-together ☕️
      content: 'Share your knowledge with the group and explore exciting new topics together! and get free foods and drinks! Enjoy!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: enjoy.jpg
    - title: The greatest community of UNR
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: bsa.jpg
      link:
        icon: contact
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
