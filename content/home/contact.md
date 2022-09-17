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
  email: example@gmail
  phone: 65 900001
  address:
    street: xxx
    city: Singapore
    postcode: '94305'
    country: Singapore
  directions: Enter Building XX and take the lift to Office xx on Floor XX
  office_hours:
    - 'Weekdays 09:00 to 17:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Twitter
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom 
      link: 'https://zoom.com'

design:
  columns: '2'
---
