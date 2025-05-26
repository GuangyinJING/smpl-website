---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Welcome to visit us. Our lab locates in Xi'An city, the old capital of acient China. We essentially root in our physics background included in the School of Physics in Northwest University, one of oldest university in China. Not as indicated by the university name, we are not literally in the nortwest of China, rather we are almost locating in the geological center of China. Feel free to contact us for a visit, or vitual discussion, exchange ideas or city visit.
      email: jing@nwu.edu.cn
      phone: +86 29 8830 3679
      address:
        street: 1 Xuefu Dadao, Chang'An Qu
        city: Xi'An
        region: ShaanXi
        postcode: '710127'
        country: China
        country_code: CN
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
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
