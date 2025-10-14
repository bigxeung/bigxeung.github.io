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
      text: |
        <br>
        
        **빅승의 작업실**에 오신 것을 환영합니다. 프로듀싱과 프로그래밍을 동시에 하는 꿈을 좇는 사나이입니다.

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
      view: card
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
