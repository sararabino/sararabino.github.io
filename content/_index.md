---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:

  # SEZIONE 1: BIO
  - block: resume-biography-3
    id: about
    content:
      username: admin
      text: ""
      button:
        text: "Download CV"
        url: "/uploads/resume.pdf"
      headings:
        about: ""
        education: ""
        interests: ""
    design:
      filename: vigna_sfondo.webp
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

        **Making a Difference? The Role of Social Impact in College Major Choice**  
        Joint with Ana Brás-Monteiro and Samantha Stelnicki

        **Is Social Learning Gendered?**  
        Joint with Kobbina Awuah, Stine Helmke, Rafael Hernández-Pachón, Urša Krenk,
        Daniela Santos Cárdenas, and David Yanagizawa-Drott
    design:
      columns: "1"

  # SEZIONE 3: POLICY - INTRO (Markdown)
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
    design:
      columns: "1"

  # SEZIONE 4: POLICY - REPORTS (Collection a 2 colonne forzate)
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
      columns: "1"

---
