---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:

  # SEZIONE 1: BIO
  - block: resume-biography-3
    id: about
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: '/uploads/resume.pdf'
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  # SEZIONE 2: RESEARCH
  - block: markdown
    id: research
    content:
      title: "Research"
      subtitle: "Work in progress"
      text: |
        **Work in Progress**

        **Making a Difference? The Role of Social Impact in College Major Choice**  
        Joint with Ana Brás-Monteiro and Samantha Stelnicki

        **Is Social Learning Gendered?**  
        Joint with Kobbina Awuah, Stine Helmke, Rafael Hernández-Pachón, Urša Krenk,
        Daniela Santos Cárdenas, and David Yanagizawa-Drott
    design:
      columns: '1'

  # SEZIONE 3: PUBLICATIONS
  - block: collection
    id: publications
    content:
      title: "Featured Publications"
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # SEZIONE 4: TEACHING
  - block: collection
    id: teaching
    content:
      title: "Teaching Experience"
      filters:
        folders:
          - teaching
    design:
      view: card

  # SEZIONE 5: POLICY
  - block: markdown
    id: policy
    content:
      title: "Policy"
      text: |
        **Think-Tank Tortuga**  
        I was part of the Think-Tank Tortuga. Tortuga is an Italian think-tank of
        Economics students and young researchers. We publish articles on economic
        issues of current relevance, with particular attention to their policy
        implications.  
        [Visit the official website](https://www.tortuga-econ.it/)

        You can add your *Policy Reports* here.
    design:
      columns: '1'

  # SEZIONE 6: OTHER INTERESTS
  - block: markdown
    id: other
    content:
      title: "Other Interests"
      text: |
        This section is dedicated to my hobbies outside of academia.

        **Sketches:** Hand-drawn pencil sketches.  
        **Wines:** Our family vineyard, *Le Due Sorelle*.
    design:
      columns: '1'

---
