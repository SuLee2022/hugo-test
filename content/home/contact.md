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
  email: test@example.gmail
  phone: 65 888 888
  address:
    street: XX
    city: Singapore 
    postcode: '94305'
    country: Singapore 
  directions: Enter XX Building and take the lift to Office xx on Floor xx
  office_hours:
    - 'Weekdays 09:00 to 17:00'
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: DM 
      link: 'https://linkedin.com'
    - icon: video
      icon_pack: fas
      name: Zoom
      link: 'https://zoom.com'

design:
  columns: '2'
---
