---
# Leave the homepage title empty to use the site title
title:
date: 2023-6-17
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
     
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to say hi and introduce yourself!
      # Contact (add or remove contact options as necessary)
      email: yia@umich.edu
      appointment_url: 'https://calendar.app.google/AMsKQHJLwsXDu18g9'
      address:
        street: 440 Church St
        city: Ann Arbor
        region: MI
        postcode: '48109'
        country: United States
        country_code: US
      directions: Office 2032 on Floor 2
      office_hours:
        - 'Workday 9:00 to 17:00'

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
