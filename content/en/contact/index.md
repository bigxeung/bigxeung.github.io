---
title: Contact
date: 2022-10-24
type: landing
weight: 60

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        <div style="text-align: justify;">Feel free to contact me if you have any questions.</div>
      email: bigxeung@gmail.com
      address:
        street: 567 Baekje-daero
        city: Jeonju-si
        region: Jeollabuk-do
        postcode: '54896'
        country: South Korea
        country_code: KR
      coordinates:
        latitude: '35.8469'
        longitude: '127.1293'
      directions: Come to Engineering Building 7.
      office_hours:
        - 'Monday 09:00 ~ 13:00'
        - 'Tuesday 12:00 ~ 14:00'
        - 'Wednesday 09:00 ~ 10:00'
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