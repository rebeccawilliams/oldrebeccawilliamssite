---
title: Contact
sections:
  - title: Contact
    subtitle: Get in Touch
    title_align: center
    content: |
      #### Do not hestiate to get in touch regarding:

      *   Press
      *   Speaking
      *   Research and Writing
      *   Consultancy
    content_align: left
    form_position: top
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: Request Type
    form_action: 'mailto:rebecca@rebeccawilliams,us'
    form_fields:
      - input_type: email
        name: Email
        label: Email
        default_value: you@email.com
        options:
          - 'Name '
          - Email
          - Request
          - lorem-ipsum
          - Where are you?
        is_required: true
        type: form_field
      - input_type: text
        name: Name Name
        label: Name
        default_value: Name Name
        options: []
        is_required: true
        type: form_field
      - input_type: select
        name: Request Type
        label: Request Type
        options:
          - Press
          - Speaking
          - Research and Writing
          - Consultancy
        is_required: true
        type: form_field
      - input_type: textarea
        name: Message
        label: Request
        options: []
        is_required: true
        type: form_field
    submit_label: Submit
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: secondary
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
