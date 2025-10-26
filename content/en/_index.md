---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: Welcome to Bigxeung's Studio
          content: A space where music and code meet.
          align: center
          background:
            image:
              filename: welcome.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#666'
        - title: PRODUCER
          content: 'Crafting new beats that move the world.'
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
          align: left
          background:
            image:
              filename: coders.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
    design:
      is_fullscreen: true
      loop: true
      interval: 7000

  - block: about.biography
    id: about
    content:
      title: About Me
      username: bigxeung

  - block: collection
    content:
      id: section-1
      title: Projects
      subtitle:
      text:
      count: 5
      offset: 0
      order: desc
      filters:
        folders:
          - project
    design:
      view: custom.cards
      columns: '2'

  - block: collection
    id: gallery
    content:
      title: Gallery
      filters:
        folders:
          - gallery
    design:
      view: custom.cards
      columns: '3'
      css_class: "gallery-box"

  - block: contact
    id: contact
    content:
      title: Contact
      text: 'My contact details are below.'
      email: bigxeung@gmail.com
      coordinates:
        latitude: '35.846906'
        longitude: '127.129432'
      directions: Find me in Building 7, Room 301
---