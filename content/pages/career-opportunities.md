---
type: PageLayout
title: Career opportunities
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: I'm actively looking for my next challenge!
      color: text-dark
    subtitle: Please reach out if interested.
    text: |
      Feel free to reach out at M: 077067 78347 or Benjamin.s.v.lopez\@gmail.com
    actions:
      - type: Button
        label: Contact me now
        altText: ''
        url: 'mailto:Benjamin.s.v.lopez@gmail.com'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Link
        label: See My Experience
        altText: ''
        url: /pricing
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/andrew-neel-cckf4TsHAuw-unsplash.jpg
      altText: Unblock your team boost your time to production preview
      elementId: ''
    badge:
      type: Badge
      label: Career opportunities
      color: text-primary
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
  - type: DividerSection
    title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
  - type: DividerSection
    title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic Section With A Form
      color: text-dark
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
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
slug: /career opportunities
seo:
  type: Seo
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create
  socialImage: /images/main-hero.jpg
  metaTags: []
---