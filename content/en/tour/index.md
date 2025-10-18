---
title: Tour
date: 2022-10-24
type: landing
menu:
  main:
    name: Tour
    weight: 10


sections:
  - block: slider
    content:
      slides:
      - title: Welcome to BIGXEUNG's Workshop
        content: Where music and code meet.
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: PRODUCER
        content: 'Creating new beats that move the world.'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: PROGRAMMER
        content: 'Bringing ideas to life with logical code.'
        align: right
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 7000
---
