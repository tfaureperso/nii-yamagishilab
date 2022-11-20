---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: ylab-pr@nii.ac.jp #zlin
  # phone: 888 888 88 88 #zlin
  twitter: https://twitter.com/yamagishilab
  address:
    street: 2-1-2 Hitotsubashi, Chiyoda-ku
    city: Tokyo
    region: JP
    postcode: '101-8430'  
    country: Japan
    country_code: JPN
  coordinates:
    latitude: '35.69280'
    longitude: '139.757946'
  directions: '1313' 
  # office_hours:
  #   - 'Monday to Friday: 09:00 to 17:00'
  #   # - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
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
---

Send us a message.
