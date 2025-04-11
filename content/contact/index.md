---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Контакты
      text: |-
        Обращайтесь по любым вопросам!
      email: sci@pfur.ru
      phone: 8 (495) 952-26-44
      address:
        street: Орджоникидзе
        city: Москва
        region: МО
        postcode: '94305'
        country: Российская федерация
        country_code: РФ
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Заходите к нам - мы везде
      office_hours:
        - ' С понедельника по субботу с 08:00 до 22:00'
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
