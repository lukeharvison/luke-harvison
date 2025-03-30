---
type: PageLayout
title: Contact
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Feel free to reach out to me!
      color: text-dark
    subtitle: Contact me using this form.
    text: "Or here \U0001F447\_\n\nEmail: <chooseluke@gmail.com>\n"
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: /contact
isDraft: false
seo:
  type: Seo
  metaTitle: Contact
  metaDescription: Contact Luke
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
