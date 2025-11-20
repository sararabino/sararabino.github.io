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

# SEZIONE 3: POLICY - INTRO
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

# 🔄 SEZIONE 4: POLICY - REPORTS (Collection AGGIORNATA con Padding)
- block: collection
  id: reports
  content:
    title: ""
    filters:
      folders:
        - reports
      exclude_featured: false
    count: 5
  design:
    view: citation
    columns: 1
    spacing:
      padding: [4, 0, 4, 0] # FIX: Aggiunge 4 unità (rem) di padding in alto e in basso.

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
