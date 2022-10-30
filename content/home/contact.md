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
  email: arthur.novaesdeamori@ucalgary.ca
  phone: +1 (825) 365-8478
  address:
    street: 2500 University Dr. NW
    city: Calgary
    region: AB
    postcode: 'T2N1N4'
    country: Canada
    country_code: CA
  coordinates:
    latitude: '51.0783'
    longitude: '-114.1346'
design:
  columns: '2'
---
