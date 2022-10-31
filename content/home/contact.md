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
  email: ngharavi@ece.ubc.ca
  # phone: 888 888 88 88
  address:
    street:
    city: Vancouver
    region: BC
    postcode:
    country: Canada
    country_code:
  coordinates:
    latitude: 
    longitude:
  directions: 
  office_hours:
    # - 'Monday 10:00 to 13:00'
    # - 'Wednesday 09:00 to 10:00'
  appointment_url: ''
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Connect with me!
      link: 'https://linkedin/in/niloo9876'
    # - icon: video
    #   icon_pack: fas
    #   name: Zoom Me
    #   link: 'https://zoom.com'

design:
  columns: '2'
---
