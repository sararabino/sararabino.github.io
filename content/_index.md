---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  # SEZIONE 1: BIOGRAFIA (ID: about o il default per l'homepage)
  - block: resume-biography-3
    id: about
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  # SEZIONE 2: RICERCA (ID: research - per il link del menu)
  - block: markdown
    id: research
    content:
      title: '🔬 Research '
      subtitle: 'Work in proges'
      text: |
        Work in progress
 :
Making a Difference? The Role of Social Impact in College Major Choice
Joint with Ana Brás-Monteiro and Samantha Stelnicki
 
Is Social Learning Gendered?
Joint with Kobbina Awuah, Stine Helmke, Rafael Hernández-Pachón, Urša Krenk, Daniela Santos Cárdenas, and David Yanagizawa-Drott
 
    design:
      columns: '1'

  # SEZIONE 3: PUBBLICAZIONI (ID: publications - Collezione, se preferisci un'altra lista)
  - block: collection
    id: publications 
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # SEZIONE 4: DIDATTICA / ESPERIENZA (ID: teaching - per il link del menu)
  - block: collection
    id: teaching # Usiamo 'teaching' come ID, anche se il contenuto è Experience/Courses
    content:
      title: Teaching Experience
      filters:
        folders:
          - teaching # Assumiamo che la cartella sia 'teaching'
    design:
      view: card

  # SEZIONE 5: POLICY (ID: policy - per il link del menu)
  - block: markdown
    id: policy
    content:
      title: '📢 Policy & Outreach'
      text: |
        **Think-Tank Tortuga**
        I was part of the Think-Tank Tortuga. Tortuga is an Italian think-tank of Economics students and young researchers. We publish newspaper articles which focus on particular economic issues of current relevance, devoting particular attention to their policy implications. We collaborate with institutions and political parties in projects of policy drafting and economic analysis. [Click here to visit our official website](https://www.tortuga-econ.it/)
        
        [Link alla sezione Policy Reports che hai definito]
    design:
      columns: '1'
      
  # SEZIONE 6: OTHER INTERESTS (ID: other - per il link del menu)
  - block: markdown
    id: other
    content:
      title: '🎨 Other Interests (Sketches & Wines)'
      text: |
        This section is dedicated to my hobbies outside of academia.
        
        **Sketches:** Hand-drawn pencil sketches.
        **Wines:** Our family vineyard, 'Le Due Sorelle'.
    design:
      columns: '1'
      
  # Rimuoviamo blocchi obsoleti (news, talks, cta-card, ecc.) se non necessari.
---
