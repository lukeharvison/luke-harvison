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
            - pl-0
            - pr-0
            - pt-0
            - pb-0
          margin:
            - mt-0
            - ml-0
            - mb-0
            - mr-0
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
      - content/pages/blog/top-ten-lessons-we-learned.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: two-col-grid
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
    showExcerpt: true
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
      styles:
        self:
          textAlign: left
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
            - pt-20
            - pb-20
            - pl-20
            - pr-20
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
      styles:
        self:
          textAlign: left
    colors: bg-light-fg-dark
    type: GenericSection
    styles:
      self:
        justifyContent: flex-end
        alignItems: flex-end
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
