---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/milad-fakurian-M8FzmNMBYek-unsplash.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: |+
      ## **Hi, I'm Ishrath**

      ## **Data analyst soon to be Data Scientist**

      ## **Love to bring ideas to life**

      ## **CSE - B.Tech - Junior @ RGUKT RK Valley**

    media:
      type: ImageBlock
      url: /images/R200453_SHAIK_MAHAMMAD_ISHRATH.jpg
      altText: Hero image
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |+
          **2022-2026**

          *   Bachelors of Technology - Computer Sciense - RGUKT RK Valley

          **2020-2022**

          *   Pre University Course - RGUKT RK Valley

          **2019-2020**

          *   SSC - Sree Krishna English Medium High School

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: >+
          **2024**


          *   Digital Content Creation Coordinator @[ Student Recreation Center
          - RGUKT
          RKV](https://www.linkedin.com/company/src-rgukt-rkvalley/mycompany/)


          **2023**


          *   Graphic Designer @ Abhiyanth 2023 - Annual Fest


          **2022 April - 2023 June**


          *   Design and Editing Coordinator
          @[RGURAA](https://rguktrkv.ac.in/alumni/)

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
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
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: Python
      - type: Label
        label: C
      - type: Label
        label: Tableau
      - type: Label
        label: MS Excel
      - type: Label
        label: MySql
      - type: Label
        label: Power BI
      - type: Label
        label: Bootstrap
      - type: Label
        label: HTML
      - type: Label
        label: JavaScript
        url: ''
      - type: Label
        label: Numpy
        url: ''
      - type: Label
        label: Pandas
        url: ''
      - type: Label
        label: Canva
        url: ''
      - type: Label
        label: Matplotlib
        url: ''
      - type: Label
        label: Notion
        url: ''
      - type: Label
        label: Figma
        url: ''
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
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
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
