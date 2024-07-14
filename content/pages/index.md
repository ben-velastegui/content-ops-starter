---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Welcome to my portfolio website!
      color: text-dark
      type: TitleBlock
      styles:
        self:
          textAlign: left
    subtitle: Innovative. Analytical. Driven.
    text: ''
    actions:
      - type: Link
        altText: LinkedIn
        url: 'https://www.linkedin.com/in/ben-lopez-ba-msc-15041a223/'
        showIcon: true
        icon: linkedin
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        altText: GitHub
        url: 'https://github.com/Ben-s-v-Lopez'
        showIcon: true
        icon: github
        iconPosition: left
        style: secondary
        elementId: ''
      - label: Projects
        altText: ''
        url: /Projects
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
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
    media:
      type: ImageBlock
      url: /images/2330859 1.jpg
      altText: Image alt text placeholder
      elementId: ''
      styles:
        self:
          borderRadius: medium
          padding:
            - pt-0
            - pl-0
            - pb-0
            - pr-0
          margin:
            - mt-0
            - ml-48
            - mb-0
            - mr-48
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
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
  - type: GenericSection
    title:
      type: TitleBlock
      text: Data Scientist
      color: text-dark
      styles:
        self:
          fontWeight: 400
          textAlign: left
    subtitle: Innovating with Machine Learning & Analytics
    text: >
      A London based data scientist. I hold a Master's degree in Data Science &
      Analytics from Brunel University and a Bachelor's degree in Marketing from
      Richmond American University. My work focuses on integrating machine
      learning and data analytics to drive innovative business solutions.


      I'm passionate about using tech to tackle real world problems. My
      experience is in bioinformatics, ESG analytics, climate science, and the
      financial markets.
    actions: []
    badge:
      type: Badge
      label: KEY INSIGHTS OF A
      color: text-primary
      styles:
        self:
          textAlign: left
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mr-56
          - ml-72
        padding:
          - pt-8
          - pb-8
        flexDirection: row
        alignItems: flex-start
        justifyContent: flex-start
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
  - type: CarouselSection
    title: null
    subtitle: ''
    items:
      - title: BioTech
        tagline: Industry interests
        subtitle: Advancing Biological Treatments through Data Analytics
        text: >
          I am passionate about Biotech to apply data analytics and machine
          learning in the discovery and development of innovative biological
          treatments.
        image:
          altText: Maria Walters
          styles:
            self:
              borderRadius: large
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: Sustainable Finance
        tagline: Industry interests
        subtitle: Promoting Ethical Investing with ESG Analytics
        text: >
          I want to work in the finance industry to apply my expertise in ESG
          analytics and machine learning, helping organizations make data-driven
          investment decisions that promote sustainability and ethical
          practices.
        image:
          altText: John Doe
          styles:
            self:
              borderRadius: large
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: HealthTech
        tagline: Industry interests
        subtitle: 'Innovating Diagnostic Accuracy with Analytics, Machine Learning, & AI'
        text: >
          I want to work in HealthTech to develop predictive models and
          personalized treatment plans that enhance patient care and optimize
          healthcare resources.
        image:
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
        padding:
          - pt-7
      subtitle:
        textAlign: center
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pl-12
          - pb-12
          - pr-12
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
