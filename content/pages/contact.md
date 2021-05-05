---
title: Contact
sections:
  - type: hero_section
    title: Contact
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: primary
  - type: form_section
    content: >-
      ### Billing

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.

      ### Privacy

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Press
          - Speaking
          - Research & Writing
          - Consultancy
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: secondary
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
    background_color: none
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
