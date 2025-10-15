---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        빅승의 작업실
      image:
        filename: welcome.jpg
        filters:
          brightness: 0.7
      text: |
        <br>
        
        **빅승의 작업실**에 오신 것을 환영합니다. 프로듀싱과 프로그래밍을 동시에 하는 꿈을 좇는 사나이입니다.

  - block: slider
    content:
      slides:
      - title: 👋 그룹에 오신 것을 환영합니다
        content: 우리가 무엇을 하고 있는지 살펴보세요...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 런치 & 런 ☕️
        content: '그룹과 지식을 공유하고 흥미로운 새 주제를 함께 탐색하세요!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 세계적 수준의 반도체 연구실
        content: '지난달에 막 문을 열었습니다!'
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
          text: 함께하기
          url: ../contact/
    design:
      slide_height: ''
      is_fullscreen: false
      loop: true
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
