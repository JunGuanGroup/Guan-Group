---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      
      email: guanjun@cuhk.edu.cn
      phone: +86 (0755)23519738
      address:
        street: 2001 Longxiang Boulevard
        city: Shenzhen
        region: Guangdong Province
        postcode: '518172'
        country: China
        country_code: CN
      coordinates:
        latitude: '22.69229'
        longitude: '114.21005'
    
      
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
          filename: Campus Map.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: 
      css_class: fullscreen
---
