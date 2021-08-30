---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      Mbôlôani ! Merci beaucoup pour votre intérêt à travailler ensemble.
      Veuillez remplir le formulaire de contact ci-dessous ou envoyez-nous un
      e-mail à yoal9998@gmail.com 
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nom
        default_value: Votre nom
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Votre addresse mail
        is_required: true
      - input_type: select
        name: subject
        label: Motif
        default_value: S'il vous plaît choisissez le motif
        options:
          - Création de site(s) web
          - Création de logo(s)
          - Création de bannière(s) publicitaire(s)
          - Création de prototypes
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
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
