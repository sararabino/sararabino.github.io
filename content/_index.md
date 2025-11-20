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

      **Making a Difference? The Role of Social Impact in College Major Choice** Joint with Ana Brás-Monteiro and Samantha Stelnicki

      **Is Social Learning Gendered?** Joint with Kobbina Awuah, Stine Helmke, Rafael Hernández-Pachón, Urša Krenk,
      Daniela Santos Cárdenas, and David Yanagizawa-Drott
  design:
    columns: "1"

# SEZIONE 3: POLICY - INTRO
- block: markdown
  id: policy
  content:
    title: "Policy"
    text: |
      I was part of the **Think-Tank Tortuga**. Tortuga is an Italian think-tank of
      Economics students and young researchers. We publish articles on economic
      issues of current relevance, with particular attention to their policy
      implications.  
      [Visit the official website](https://www.tortuga-econ.it/)
  design:
    columns: "1"

# SEZIONE 4: POLICY - REPORTS (Collection a 2 colonne)
- block: collection
  id: reports
  content:
    title: ""
    text: |
      ### Policy Reports I contributed to:

      * [2022] Introduciamo il salario minimo?[Italian](https://www.tortuga-econ.it/2023/01/10/introduciamo-il-salario-minimo/)
      * [2021] Parità e occupazione in Europa[Italian](https://www.tortuga-econ.it/2021/03/09/parita-e-occupazione-in-europa-strategie-analisi-azioni-verso-ununione-delluguaglianza/)
      * [2020] VIUS – Vita in un sorso[Italian](https://www.tortuga-econ.it/2021/11/24/vius-vita-in-un-sorso-policy-report/)
      * [2019] Mamma ho preso l’aereo: la nuova fuga dei cervelli italiani[Italian](https://www.tortuga-econ.it/2019/05/08/mamma-ho-preso-laereo-la-nuova-fuga-dei-cervelli-italiani-il-report/)
      * [2019] Game of Brains, 21st century Italian Emigration[English](https://media.algebris.com/algebris_policy_research_forum/Issue-3_Game-of-Brains-21st-century-Italian-emigration.pdf)
    columns: "1"

# SEZIONE 5: POLICY - OTHER CONTRIBUTIONS
- block: markdown
  id: policy-articles
  content:
    title: ""
    text: |
      ### Some Other Contributions (all in Italian):

      * [2022] [Se il salario minimo aumenta anche gli stipendi in nero](https://www.informazionesenzafiltro.it/se-il-salario-minimo-aumenta-anche-gli-stipendi-in-nero)
      * [2022] [Working poor, l’Italia non sa contarli. Il salario minimo li aiuterebbe?](https://www.informazionesenzafiltro.it/working-poor-italia-salario-minimo)
      * [2022] [Non tutte le imprese possoo permettersi il salario minimo](https://www.informazionesenzafiltro.it/non-tutte-le-imprese-possono-permettersi-il-salario-minimo)
      * [2020] [La disoccupazione ai tempi del coronavirus](https://www.pandorarivista.it/articoli/la-disoccupazione-ai-tempi-del-coronavirus/)
      * [2020] [Come utilizzare le risorse europee per attrarre talenti in Italia](https://www.fanpage.it/economia/come-utilizzare-le-risorse-europee-per-attrarre-talenti-in-italia/)
      * [2019] [Donne e lavoro: cosa (non) fa lo stato](https://www.econopoly.ilsole24ore.com/2019/03/08/donne-lavoro-stato/)
  design:
    columns: "1"

---
