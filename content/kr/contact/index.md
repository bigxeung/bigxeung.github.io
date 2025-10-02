---
title: 연락처
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: 연락처
      text: |-
        궁금한 점이 있으시면 언제든지 아래 연락처나 양식을 통해 문의해주세요.
      # 이메일, 전화번호, 주소 등은 실제 정보로 수정해주세요.
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: 1번 건물로 들어오셔서 계단을 이용해 2층 200호로 오시면 됩니다.
      office_hours:
        - '월요일 10:00 ~ 13:00'
        - '수요일 09:00 ~ 10:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'

      # 이메일과 전화번호를 텍스트로 표시할지, 자동으로 링크를 걸지 설정합니다.
      autolink: true

      # 이메일 전송 폼 설정
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # 스팸 방지를 위한 CAPTCHA 사용 여부
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