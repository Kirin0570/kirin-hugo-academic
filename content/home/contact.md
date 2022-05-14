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
  email: qli478@wisc.edu
  phone: 608-262-5767
  address:
    street: 1300 University Avenue
    city: Madison
    region: WI
    postcode: '53706'
    country: United States
    country_code: US
  coordinates:
    latitude: '43.0738'
    longitude: '-89.4074'
  directions: 1245F Medical Sciences Center

design:
  columns: '2'
---
