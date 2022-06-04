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
  email: lkhanina.study@gmail.com
  phone: 89162457097
  address:
    street: st. Miklukho-Maclay, 6
    city: Moscow
    postcode: '117198'
    country: Russia
    country_code: RU
  office_hours:
    - 'Monday 15:00 to 18:00'
    - 'Wednesday 10:30 to 18:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
