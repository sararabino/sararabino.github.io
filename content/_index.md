---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "3rem"

sections:

# SEZIONE 1: About (con sfondo immagine e testo)
- block: resume-biography-3 # NESSUNO SPAZIO O TAB PRIMA DEL TRATTINO
  id: about
  content:
    # Choose a user profile to display (a folder name within `content/authors/`)
    username: admin
    text: ''
    # Show a call-to-action button under your biography? (optional)
    button:
      text: Download CV
      url: uploads/resume.pdf
    headings:
      about: 'About'
      interests: ''
  design:
    background:
      image:
        filename: peakpx.jpg
    # Avatar customization
    avatar:
      size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
      shape: circle # Options: circle (default), square, rounded
    
# SEZIONE 2: RESEARCH (Allineamento Corretto)
- block: markdown
  id: research
  content:
    title: "Research"
    subtitle: "Work in progress"
    text: |
      **Work in Progress**

      **Making a Difference? The Role of Social Impact in College Major Choice** Joint with [Ana Brás-Monteiro](https://anabrasmonteiro.com/) and [Samantha Stelnicki](https://sites.google.com/view/samanthastelnicki/home)

      **Is Social Learning Gendered?** Joint with Kobbina Awuah, [Stine Helmke](https://www.econ.uzh.ch/en/people/graduatestudents/helmke.html), [Rafael Hernández-Pachón](https://sites.google.com/view/rafaelhernandezpachon), [Urša Krenk](https://ursakrenk.com/),
      [Daniela Santos Cárdenas](https://www.danielasantoscardenas.com/), and [David Yanagizawa-Drott](https://yanagizawadrott.com/)
  design:
    columns: "1"

# 🔄 SEZIONE 3: TEACHING (NUOVO LAYOUT CON ICONE)
- block: markdown
  id: teaching # ANCORA: /#teaching
  content:
    title: "Teaching" # Titolo esatto
    text: |
      ### University of Zurich
      
      {{< icon name="academic-cap" pack="hero" >}} **Lecturer** (The Economics of Gender Norms, BA), 2024
      
      {{< icon name="academic-cap" pack="hero" >}} **Teaching Assistant** (Econometrics for Research Students, PhD), 2023–2024
      
      <br>

      ### Bocconi University
      
      {{< icon name="academic-cap" pack="hero" >}} **Teaching Assistant** (Computer Science, BA), 2016–2020
  design:
    columns: '1'

# SEZIONE 4: POLICY - INTRO
- block: markdown
  id: policy
  content:
    title: "Policy"
    text: |
      I was part of the **Think-Tank Tortuga**. Tortuga is an Italian think-tank of
      Economics students and young researchers. We publish articles on economic
      issues of current relevance, with particular attention to their policy
      implications. We collaborate with institutions and political parties in projects of policy drafting and economic analysis.
   
      [Visit the official website](https://www.tortuga-econ.it/)
  design:
    columns: "1"
    spacing:
      bottom: 0      # reduces space AFTER this section
  
# 🔄 SEZIONE 5: POLICY - REPORTS (Collection con titolo ripristinato)
- block: collection
  id: reports
  content:
    title: "Some Policy Reports I contributed to:"
    filters:
      folders:
        - reports
      exclude_featured: false
    count: 5
  design:
    view: citation
    columns: 1
---
