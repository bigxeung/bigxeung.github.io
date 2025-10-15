---
title: 연락처
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: 연락처
      text: |-
        궁금한 점이 있으시면 언제든지 연락주세요.
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: 567 Baekje-daero, Deokjin-gu
        city: Jeonju-si
        region: Jeollabuk-do
        postcode: '54896'
        country: 대한민국
        country_code: KR
      coordinates:
        latitude: '35.8469'
        longitude: '127.1293'
      directions: 공과대학 7호관으로 오세요.
      office_hours:
        - '월요일 10:00 ~ 13:00'
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