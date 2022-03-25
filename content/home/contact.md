---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

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
      captcha: false

  # Contact details (edit or remove options as required)
  email: steinguo@outlook.com
  phone: +86 19929062698
  address:
    street: No. 27 of Shanda Rd. S
    city: Jinan
    region: Shandong
    postcode: '250014'
    country: China
    country_code: CHN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  contact_links:
  
design:
  columns: '2'
---
