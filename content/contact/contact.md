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

  email: yubin@tju.edu.cn
#  phone: 888 888 88 88
  address:
    street: Peiyang Park Campus, Tianjin University, No.135 Yaguan Road
    city: Haihe Education Park
    region: Tianjin
    postcode: '300350'
    country: China
    country_code: CHN
  coordinates:
    latitude: '38.99661'
    longitude: '117.30414'
  directions:  2st Floor, Section C, Datong Student Center
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
---

