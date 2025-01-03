---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: SECURE AI
      color: text-dark
      type: TitleBlock
    subtitle: Intelligent Automation
    text: >
      Starting a successful business is a dream for many entrepreneurs. But the
      challenges and uncertainties make it hard to predict success. SECURE AI is
      here to help. It uses advanced artificial intelligence to accurately
      forecast the chances of a startup's success.
    actions:
      - label: Get started
        altText: Secure II
        url: 'https://secure-dev-ed.develop.my.site.com/secure/'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Learn more
        altText: ''
        url: 'https://www.securecanvas.net/secure-ai'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/SECURE AI.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: SECURE 2
      color: text-primary
      type: Badge
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
  - subtitle: Award winning enterprises trust us
    images:
      - url: /images/empathy-logo.svg
        altText: Empathy logo
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Vise logo
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: Telus logo
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
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
      text: Grow your business 10x faster
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Benefits of SECURE AI
    text: |+
      ****

      *   Provides data-driven insights for better planning

      *   Acts as a reliable guide through uncertainties

      *   Highlights areas to improve in business models

      *   Helps optimize resources and strategies effectively

      *   Accurately predicts the chances of success

      *   Assists investors in evaluating opportunities

      *   Supports policymakers in creating interventions

    badge:
      label: Key Benefits
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
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
      text: TEAM SECURE
      color: text-dark
      type: TitleBlock
    subtitle: Get in touch...
    text: "© 2019, All rights reserved to Dr\_Tahseen Arshi (MoC Copyright Number: 3377)\n\n"
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
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
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
