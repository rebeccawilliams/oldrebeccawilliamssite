---
title: Contact
sections:
  - title: Contact
    title_align: center
    content: |
      Or just send an email to: rebecca@rebeccawilliams.us
    content_align: center
    form_position: top
    form_width: sixty
    form_layout: stacked
    enable_card: true
    form_id: contact
    form_action: contact
    form_fields:
      - input_type: email
        name: Your Email
        label: Your Email
        default_value: you@email.com
        options:
          - Name
          - Email
          - Request
          - Urgent?
        is_required: true
        type: form_field
    submit_label: Email
    align_vert: middle
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: form_section
    subtitle: Have a question? Be in touch.
  - title: Contact
    subtitle: Get in Touch
    title_align: left
    content: |
      ## Guidelines

      Please do not hestiate to get in touch regarding: 

      *   Press
      *   Speaking
    content_align: left
    form_position: bottom
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: Submit
    form_action: Submit
    form_fields:
      - input_type: email
        name: Email
        label: lorem-ipsum
        default_value: lorem-ipsum
        options: []
        is_required: false
        type: form_field
    submit_label: lorem-ipsum
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: form_section
seo:
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
layout: advanced
---
