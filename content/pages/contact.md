---
title: Contact
sections:
  - type: hero_section
    title: Contact
    subtitle: Have a question? Send me an email and I will be in touch soon.
    align: center
    padding_top: small
    padding_bottom: small
    has_border: true
    background_color: none
  - type: grid_section
    grid_items:
      - title: Contact
        title_align: center
        content_align: center
        actions:
          - label: Email
            url: 'email-to:rebecca@rebeccawilliams.us'
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/classic/icon-3.svg
        image_alt: Other queries icon
        image_position: top
        image_align: center
        image_has_padding: true
    grid_cols: three
    grid_gap_horiz: small
    grid_gap_vert: small
    enable_cards: true
    align: center
    padding_top: large
    padding_bottom: large
    background_color: primary
  - title: Contact
    title_align: center
    content: |
      Send me an email.
    content_align: center
    form_position: top
    form_width: sixty
    form_layout: stacked
    enable_card: true
    form_id: contact
    form_action: contact
    form_fields:
      - input_type: text
        name: Email me
        label: Email me
        default_value: lorem-ipsum
        options:
          - lorem-ipsum
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
