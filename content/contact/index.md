---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        The TecNM Campus Bahía de Banderas is a higher education institution which offers undergaduate progarmmes in Biology, Environmental Engineering, Administration and Tourism. It counts with several well equipped laboratories such as Basic Sciencie, Microbiology, Aquaculture and Zoology.
      email: julio.pg@bahia.tecnm.mx
      phone: 329 295 5951
      address:
        street: Crucero de La Cruz de Huanacaxtle S/N
        city: Bahía de Banderas
        region: Nayarit
        postcode: '63734'
        country: Mexico
        country_code: MX
      coordinates:
        latitude: '20.7644'
        longitude: '-105.3711'
      directions: From Bucerías take the exit to the right before the bridge the turn left right after the bridge.
      office_hours:
        - 'Monday to Friday 08:00 to 16:00'
      #appointment_url: 'https://calendly.com'
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
