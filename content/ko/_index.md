---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        김승현
        개인 웹사이트
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        **김승현의 개인 연구 웹사이트**에 오신 것을 환영합니다. 인공지능 연구, 교육 및 실습의 우수성을 추구합니다.

  - block: about.biography
    id: about
    content:
      title: 소개
      username: bigxeung

  - block: collection
    content:
      title: 최신 소식
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
      text: '아래에서 연락처 정보를 확인하세요.'
      email: bigxeung@gmail.com
      coordinates:
        latitude: '35.846906'
        longitude: '127.129432'
      directions: 공과대학 7호관, 301호
      contact_links:
        - icon: comments
          icon_pack: fas
          name: 포럼에서 토론하기
          link: 'https://github.com/bigxeung/bigxeung.github.io/discussions'
---
