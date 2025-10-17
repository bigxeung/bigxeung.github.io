---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Wowchemy
        Research Group
      image:
        filename: welcome.jpg
        filters:
          brightness: 0.7
      text: |
        <br>
        
        The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.

  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the Group
        content: Take a look at what we're doing...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      slide_height: ''
      is_fullscreen: false
      loop: true
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
