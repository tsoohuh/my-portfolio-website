---
type: PageLayout
title: Home
colors: colors-e
backgroundImage:
  type: BackgroundImage
  url: /images/vrju1i20b2m91.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Hey, I'm Nathan Eduard Romero!
    subtitle: >-
      I am currently a senior CS student at the University of Santo Tomas -
      College of Information and Computing Sciences. Here, I share the things
      I'm working on, doing it with love.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
    media:
      type: ImageBlock
      url: /images/Fxh1Obl2.jpg
      altText: Portrait of me
      caption: Caption of the image
      elementId: ''
  - type: LabelsSection
    title: Skills
    subtitle: What I learned so far in my journey
    items:
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: Java
        url: ''
      - type: Label
        label: HTML/CSS
        url: ''
      - type: Label
        label: ''
        url: ''
      - type: Label
        label: Javascript
        url: ''
      - type: Label
        label: C#
        url: ''
      - type: Label
        label: SQL
        url: ''
      - type: Label
        label: VSCode
        url: ''
      - type: Label
        label: Git
        url: ''
      - type: Label
        label: TailwindCSS
        url: ''
      - type: Label
        label: Docker
        url: ''
      - type: Label
        label: ''
        url: ''
      - type: Label
        label: Blender
        url: ''
      - type: Label
        label: Unity
        url: ''
      - type: Label
        label: ''
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        textAlign: center
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Want to connect?
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign up to receive updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: 'Submit '
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
