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
      url: uploads/Curriculum_Vitae_JM.pdf
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

# SEZIONE 2: RESEARCH
- block: markdown
  id: research
  content:
    title: "Research"
    subtitle: ""
    text: |
      <span class="res-label">Job Market Paper</span>

      <span class="paper-title">Making a Difference? The Role of Social Impact in College Major Choice</span>

      <span class="paper-authors">Joint with [Ana Brás-Monteiro](https://anabrasmonteiro.com/) and [Samantha Stelnicki](https://sites.google.com/view/samanthastelnicki/home)</span>

      <span class="paper-status">Draft available upon request</span>

      <span class="res-label">Work in Progress</span>

      <span class="paper-title">Is Social Learning Gendered?</span>

      <span class="paper-authors">Joint with Kobbina Awuah, [Stine Helmke](https://www.econ.uzh.ch/en/people/graduatestudents/helmke.html), [Rafael Hernández-Pachón](https://sites.google.com/view/rafaelhernandezpachon), [Urša Krenk](https://ursakrenk.com/), [Daniela Santos Cárdenas](https://www.danielasantoscardenas.com/), and [David Yanagizawa-Drott](https://yanagizawadrott.com/)</span>

      <span class="paper-status">Draft coming soon</span>

      <span class="paper-title">How Men and Women Want to Do (and Look) Good: Effective Altruism vs Warm Glow</span>

      <span class="paper-status">Piloting stage</span>
  design:
    columns: "1"

# SEZIONE 3: TEACHING
- block: markdown
  id: teaching
  content:
    title: "Teaching"
    text: |
      <span class="res-label">University of Zurich</span>

      {{< icon name="academic-cap" pack="hero" >}} <span class="teach-role">Lecturer</span> <span class="teach-course">The Economics of Gender Norms, BA, 2024</span>

      {{< icon name="academic-cap" pack="hero" >}} <span class="teach-role">Teaching Assistant</span> <span class="teach-course">Econometrics for Research Students, PhD, 2023–2024</span>

      <span class="res-label">Bocconi University</span>

      {{< icon name="academic-cap" pack="hero" >}} <span class="teach-role">Teaching Assistant</span> <span class="teach-course">Computer Science, BA, 2016–2020</span>
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
