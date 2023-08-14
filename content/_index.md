---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          icon: python
          icon_pack: fab
        - name: Cloud Computing
          icon: cloud-arrow-up
          icon_pack: fas
        - name: Statistics
          icon: chart-line
          icon_pack: fas
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: michaela.philip@emory.edu
      address:
        street: R. Randall Rollins 1516 Clifton Road
        city: Atlanta
        region: GA
        postcode: '30322'
        country: United States
        country_code: US
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
    design:
      columns: '2'
---
