---
title: Contact
sections:
  - title: Contact
    subtitle: Get in Touch
    title_align: center
    content_align: left
    form_position: bottom
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: email
    form_action: 'mailto:rebecca@rebeccawilliams.us'
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
          - Other
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
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: form_section
  - title: Stay in Touch
    content: |
      ### On Social
    actions:
      - url: 'https://www.twitter.com/internetrebecca'
        style: secondary
        has_icon: true
        icon: twitter
        icon_position: right
        new_window: true
        no_follow: false
        type: action
      - url: 'https://www.instagram.com/hannaharendtthedog/'
        style: secondary
        has_icon: true
        icon: instagram
        icon_position: right
        new_window: false
        no_follow: false
        type: action
      - url: 'https://www.linkedin.com/in/rebeccaannwilliams/'
        style: secondary
        has_icon: true
        icon: linkedin
        icon_position: right
        new_window: true
        no_follow: false
        type: action
      - url: 'https://github.com/rebeccawilliams/'
        style: secondary
        has_icon: true
        icon: github
        icon_position: right
        new_window: true
        no_follow: false
        type: action
      - label: PGP Key
        url: 'https://keybase.io/RebeccaWilliams/key.asc'
        style: secondary
        has_icon: false
        icon: arrow-left
        icon_position: right
        new_window: false
        no_follow: false
        type: action
    actions_position: bottom
    actions_width: fourty
    align: left
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: secondary
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: cta_section
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
