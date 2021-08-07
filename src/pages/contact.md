---
title: Contact
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: "Let’s build something great together.\nComplete our contact form or send us an email at:\n\nhello \\[@] b01and \\[.] com\n\n***\n\n## Offices:\n\n\U0001F30D.\n\n"
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - type: form_field
        input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - type: form_field
        input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - type: form_field
        input_type: select
        name: subject
        label: What services are you looking for?
        default_value: Please select
        options:
          - Community Management
          - Search Engine Optimization
          - Competitor Analysis
          - Dapp Testing & Controlled Group Testing
          - Content Creation
          - Video Translation
          - Video Transcribing
          - Blog-To-Video Creation
          - Social Media Management
          - Investment Analysis
          - Background Research (individual)
          - Background Research (team)
          - 'Marketing Audit (existing services) '
          - Exchange Placements
      - input_type: text
        name: Team Size
        label: Team Size
        default_value: 1-150?
        options: []
        is_required: false
        type: form_field
      - type: form_field
        input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - type: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  type: stackbit_page_meta
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
template: advanced
---
