---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:

# SEZIONE 1: BIO (con sfondo immagine e testo)
- block: resume-biography
  id: about
  content:
    username: admin
    text: |
      Ciao! I’m a fifth-year PhD student in Economics at the University of Zurich. I work at the intersection of behavioral and labor economics, with a focus on education and gender inequalities. 

      I am currently visiting Harvard University, hosted by Katherine Coffman. Happy to connect!
    button:
      text: Download CV
      url: '/uploads/resume.pdf'
    headings:
      about: ''
      education: ''
      interests: ''
  design:
    # CLASSE AGGIUNTA PER IL PADDING RESPONSIVE (MOBILE)
    css_class: 'p-4 sm:p-6 md:p-8' 

    section_size: 'xxl' 
    
    background:
      image:
        url: '/img/vigna_sfondo.jpg' 
      image_size: 'cover'       
      image_position: 'center'  
      image_parallax: true      
      overlay_color: '#000'
      overlay_alpha: 0.5 
    avatar:
      size: large
      shape: circle

# SEZIONE 2: RESEARCH
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
      **Think-Tank Tortuga** I was part of the Think-Tank Tortuga. Tortuga is an Italian think-tank of
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
    filters:
      folders:
        - reports
      exclude_featured: false
    count: 5
  design:
    view: article-grid
    columns: 2

# SEZIONE 5: POLICY - OTHER CONTRIBUTIONS
- block: markdown
  id: policy-articles
  content:
    title: ""
    text: |
      ### Some Other Contributions (all in Italian):

      * [2022] [If Minimum Wage Increases, So Do Undeclared Wages](https://www.informazionesenzafiltro.it/se-il-salario-minimo-aumenta-anche-gli-stipendi-in-nero)
      * [2022] [Working Poor: Italy Can't Count Them. Would Minimum Wage Help?](https://www.informazionesenzafiltro.it/working-poor-italia-salario-minimo)
      * [2022] [Not All Companies Can Afford the Minimum Wage](https://www.informazionesenzafiltro.it/non-tutte-le-imprese-possono-permettersi-il-salario-minimo)
      * [2020] [Unemployment in the Time of Coronavirus](https://www.pandorarivista.it/articoli/la-disoccupazione-ai-tempi-del-coronavirus/)
      * [2020] [How to Use European Resources to Attract Talent to Italy](https://www.fanpage.it/economia/come-utilizzare-le-risorse-europee-per-attrarre-talenti-in-italia/)
      * [2019] [Women and Work: What the State Does (and Does Not Do)](https://www.econopoly.ilsole24ore.com/2019/03/08/donne-lavoro-stato/)
  design:
    columns: "1"

---
