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
      title: 소개
      username: bigxeung

  - block: collection
    content:
      id: section-1
      title: 프로젝트s
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
      title: 갤러리
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
      title: 연락처
      text: '제 연락처는 아래와 같습니다.'
      email: bigxeung@gmail.com
      coordinates:
        latitude: '35.846906'
        longitude: '127.129432'
      directions: 7호관 301호로 오세요
---
