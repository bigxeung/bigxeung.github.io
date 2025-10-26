---
title: 연락처
date: 2022-10-24
type: landing
weight: 60

sections:
  - block: contact
    content:
      title: 연락처
      text: |-
        <div style="text-align: justify;">궁금한 점이 있으시면 언제든지 연락주세요.</div>
      email: bigxeung@gmail.com
      address:
        street: 567 백제대로
        city: 전주시
        region: 전라북도
        postcode: '54896'
        country: 대한민국
        country_code: KR
      coordinates:
        latitude: '35.8469'
        longitude: '127.1293'
      directions: 공과대학 7호관으로 오세요.
      office_hours:
        - '월요일 09:00 ~ 13:00'
        - '화요일 12:00 ~ 14:00'
        - '수요일 09:00 ~ 10:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---