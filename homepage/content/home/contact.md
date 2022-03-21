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
  email: gongruihao@sensetime.com
  address:
    street: No.58 Northwest 4th Ring Road
    city: Beijing
    region: Haidian District
    postcode: '100080'
    country: China
    country_code: CN
  coordinates:
    latitude: '39.9042'
    longitude: '116.4074'

design:
  columns: '2'
---
