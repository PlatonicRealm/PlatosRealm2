---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

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
  email: m.w.davies@qmul.ac.uk
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Twitter
      link: 'https://twitter.com/PlatosRealm'
    - icon: youtube
      icon_pack: fab
      name: Physically Debunked
      link: 'https://www.youtube.com/channel/UCIUZDClwsT9a8l4e2mt4flA'
    - icon: youtube
      icon_pack: fab
      name: Shots in the Quark
      link: 'https://www.youtube.com/channel/UC2MlYzJBy3RCMMbViQE0dew'

design:
  columns: '2'
---
