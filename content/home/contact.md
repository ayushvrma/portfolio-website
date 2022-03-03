---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact Me
subtitle: Would love to hear from you!

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

  # Contact details (edit or remove options as required)
  email: ayush8402@gmail.com
  phone: +91-8604091203
  address:
    street: 50 Indrapuri
    city: Lucknow
    region: Uttar Pradesh
    postcode: '226023'
    country: India
    country_code: IN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  office_hours:
    - '12-15 hours a week'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Twitter
      link: 'https://twitter.com/_oyus_'

design:
  columns: '2'
---
