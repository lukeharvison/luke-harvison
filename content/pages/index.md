---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Personal Website for Luke Harvison
      color: text-dark
      type: TitleBlock
    subtitle: CS @ Vandy. BHM -> Nashville
    text: >
      Interested in personal health and business. Always down to meet cool
      people.
    actions:
      - label: Visit articles
        altText: ''
        url: /blog
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    media:
      url: /images/profilepic.jpg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
      styles:
        self:
          padding:
            - pl-8
            - pr-8
            - pt-8
            - pb-8
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - posts:
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Subscribe
      color: text-dark
      type: TitleBlock
    subtitle: Get pinged in the inbox
    text: |
      Testing the waters with a subscribe box...
    media:
      fields:
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
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
          justifyContent: center
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Subscribe
        showIcon: false
        icon: arrowRight
        iconPosition: left
        style: primary
        elementId: null
    badge:
      label: sub for more
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
    styles:
      self:
        justifyContent: center
        alignItems: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
