---
type: PageLayout
title: Ishrath's Portfolio
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/milad-fakurian-M8FzmNMBYek-unsplash.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: HeroSection
    title: >-
      I’m Shaik Mahammad Ishrath, a passionate Data Analyst and an aspiring Data
      Scientist.
    subtitle: >-
      As a data analyst, I believe in the power of data to drive decisions and
      create meaningful change. I specialize in transforming complex data into
      clear, actionable insights that can help solve real-world problems.
    actions:
      - type: Button
        label: Know more about me
        altText: ''
        url: /projects
        showIcon: true
        icon: arrowRightCircle
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: LabelsSection
    title: Skills
    subtitle: Skills and Tools I'm habitual with
    items:
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: C
        url: ''
      - type: Label
        label: MS Excel
        url: ''
      - type: Label
        label: Tableau
        url: ''
      - type: Label
        label: MySql
        url: ''
      - type: Label
        label: Power BI
        url: ''
      - type: Label
        label: Bootstrap
        url: ''
      - type: Label
        label: HTML
        url: ''
      - type: Label
        label: JavaScript
        url: ''
      - type: Label
        label: Pandas
        url: ''
      - type: Label
        label: Numpy
        url: ''
      - type: Label
        label: Matplotlib
        url: ''
      - type: Label
        label: Canva
        url: ''
      - type: Label
        label: Notion
        url: ''
      - type: Label
        label: Figma
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
        justifyContent: center
      title:
        textAlign: center
      subtitle:
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
    variant: variant-d
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Made with love
    title: Projects
---
