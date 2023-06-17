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
          
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. student
          company: University of Michigan
          company_url: ''
          company_logo: org-gc
          location: Ann Arbor, MI, US
          date_start: '2023-01-01'
          date_end: ''
          description: |2-

        - title: Undergraduate student
          company: Southern University of Science and Technology
          company_url: ''
          company_logo: org-x
          location: Shenzhen, Guangong, China
          date_start: '2018-09-01'
          date_end: '2022-07-02'
          description: 
      columns: '2'
      
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
      
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
      
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
