---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

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

  - block: about.biography
    id: about
    content:
      title: Biography
      username: bigxeung

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: simple-title
      columns: '1'

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 'My contact details are below.'
      email: bigxeung@gmail.com
      coordinates:
        latitude: '35.846906'
        longitude: '127.129432'
      directions: Enter Building 7, Room 301
      contact_links:
        - icon: comments
          icon_pack: fas
          name: Discuss on Forum
          link: 'https://github.com/bigxeung/bigxeung.github.io/discussions'
---
