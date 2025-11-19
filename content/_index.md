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

  # SEZIONE 3: TEACHING
  - block: collection
    id: teaching
    content:
      title: "Teaching Experience"
      filters:
        folders:
          - teaching
    design:
      view: card

  # SEZIONE 4: POLICY (Reports statici di Tortuga)
  - block: markdown
    id: policy
    content:
      title: "Policy" # Titolo: mantenuto "Policy"
      text: |
        I was part of the **Think-Tank Tortuga**. Tortuga is an Italian think-tank of
        Economics students and young researchers. We publish articles on economic
        issues of current relevance, with particular attention to their policy
        implications. [Visit the official website](https://www.tortuga-econ.it/)

        ### Policy Reports I contributed to:

        * [2023] [Introduciamo il salario minimo? (Italian)](https://www.tortuga-econ.it/2023/01/10/introduciamo-il-salario-minimo/)
        * [2021] [Parità e occupazione in Europa (Italian)](https://www.tortuga-econ.it/2021/03/09/parita-e-occupazione-in-europa-strategie-analisi-azioni-verso-ununione-delluguaglianza/)
        * [2020] [VIUS – Vita in un sorso (Italian)](https://www.tortuga-econ.it/2021/11/24/vius-vita-in-un-sorso-policy-report/)
        * [2019] [Mamma ho preso l’aereo: la nuova fuga dei cervelli italiani (Italian)](https://www.tortuga-econ.it/2019/05/08/mamma-ho-preso-laereo-la-nuova-fuga-dei-cervelli-italiani-il-report/)
        * [2019] [Game of Brains, 21st century Italian Emigration (English)](https://media.algebris.com/algebris_policy_research_forum/Issue-3_Game-of-Brains-21st-century-Italian-emigration.pdf)

    design:
      columns: '1'

  # SEZIONE 5: POLICY ARTICLES (Articoli pubblicati sui media - dinamici)
  - block: collection
    id: articles
    content:
      title: 'Policy Articles' # Ho chiamato la sezione dinamica "Policy Articles"
      subtitle: 'Other Contributions in Italian Media'
      filters:
        folders:
          - post # Mostra i contenuti dalla cartella content/post/
        exclude_featured: false
      count: 0 # Mostra tutti i risultati
    design:
      view: list # Mostra in formato lista (più ordinato)
      columns: 1
      
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
