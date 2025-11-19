---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:

# SEZIONE 1: BIO (Risolve Sfondo Predefinito e abilita Interests)
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
        interests: '' # <-- ESSENZIALE per mostrare la sezione Interests
    design:
      # Rimosso il blocco 'background' per ripristinare lo sfondo predefinito.
      # background:
      #   filename: vigna_sfondo.jpg
      #   image_process:
      #     filters:
      #       brightness: 0.8
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

        **Making a Difference? The Role of Social Impact in College Major Choice** Joint with Ana Brás-Monteiro and Samantha Stelnicki

        **Is Social Learning Gendered?** Joint with Kobbina Awuah, Stine Helmke, Rafael Hernández-Pachón, Urša Krenk,
        Daniela Santos Cárdenas, and David Yanagizawa-Drott
    design:
      columns: "1"

  # SEZIONE 3: POLICY - INTRO (Markdown)
  - block: markdown
    id: policy
    content:
      title: "Policy & Outreach"
      subtitle: "Think-Tank Tortuga"
      text: |
        I was part of the **Think-Tank Tortuga**, an Italian think-tank of Economics students and young researchers. We publish newspaper articles focusing on economic issues of current relevance, devoting particular attention to their policy implications. We collaborate with institutions and political parties in projects of policy drafting and economic analysis.

        [Visit the official website](https://www.tortuga-econ.it/)
    design:
      columns: "1"

  # SEZIONE 4: POLICY - POLICY REPORTS (Markdown)
  - block: markdown
    id: policy-reports
    content:
      title: ""
      text: |
        ### Policy Reports I contributed to:

        * [2022] [Introduciamo il salario minimo? (Italian)](https://www.tortuga-econ.it/2023/01/10/introduciamo-il-salario-minimo/)
        * [2021] [Parità e occupazione in Europa (Italian)](https://www.tortuga-econ.it/2021/03/09/parita-e-occupazione-in-europa-strategie-analisi-azioni-verso-ununione-delluguaglianza/)
        * [2020] [VIUS – Vita in un sorso (Italian)](https://www.tortuga-econ.it/2021/11/24/vius-vita-in-un-sorso-policy-report/)
        * [2019] [Mamma ho preso l’aereo: la nuova fuga dei cervelli italiani (Italian)](https://www.tortuga-econ.it/2021/11/24/vius-vita-in-un-sorso-policy-report/)
        * [2019] [Game of Brains, 21st century Italian Emigration (English)](https://media.tortuga-econ.it/2021/11/policy-report-game-of-brains.pdf)
    design:
      columns: "1"

# SEZIONE 5: POLICY - OTHER CONTRIBUTIONS (Markdown)
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
