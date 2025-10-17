---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 빅승의 작업실에 오신 것을 환영합니다
        content: 음악과 코드가 만나는 공간.
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: PRODUCER
        content: '세상을 움직이는 새로운 비트를 만듭니다.'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: PROGRAMMER
        content: '논리적인 코드로 아이디어를 현실로 구현합니다.'
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
      title: 소개
      username: bigxeung

  - block: collection
    content:
      title: 프로듀싱/프로그래밍
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
      title: 최신 논문
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
      title: 연락처
      subtitle:
      text: 'ig/tg : @bigxeung'
      email: bigxeung@gmail.com
      coordinates:
        latitude: '35.846906'
        longitude: '127.129432'
      directions: 전북대학교 공과대학 7호관
      contact_links:
        - icon: comments
          icon_pack: fas
          name: 포럼에서 토론하기
          link: 'https://github.com/bigxeung/bigxeung.github.io/discussions'
---
