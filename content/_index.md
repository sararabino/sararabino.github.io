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

  # SEZIONE 4: UFFICIALI POLICY REPORTS (VISUAL BOXES - da popolare nella cartella 'reports')
  - block: collection
    id: reports
    content:
      title: 'Official Policy Reports'
      filters:
        folders:
          - reports # Assumiamo una cartella reports in content/
        exclude_featured: false
      count: 5 # Mostra i 5 report ufficiali
    design:
      view: card # Visualizzazione a box con immagine
      columns: 2

  # SEZIONE 5: MEDIA ARTICLES (LINK DI TESTO STATICI)
  - block: markdown
    id: policy
    content:
      title: "Policy Articles (Media Contributions)"
      text: |
        I was part of the **Think-Tank Tortuga** (2019–2022).

        ### Other Contributions (Simple Text Links)

        * [2022] [If Minimum Wage Increases, So Do Undeclared Wages (Italian)](https://www.informazionesenzafiltro.it/se-il-salario-minimo-aumenta-anche-gli-stipendi-in-nero)
        * [2022] [Working Poor: Italy Can't Count Them. Would Minimum Wage Help? (Italian)](https://www.informazionesenzafiltro.it/working-poor-italia-salario-minimo)
        * [2022] [Not All Companies Can Afford the Minimum Wage (Italian)](https://www.informazionesenzafiltro.it/non-tutte-le-imprese-possono-permettersi-il-salario-minimo)
        * [2020] [Unemployment in the Time of Coronavirus (Italian)](https://www.pandorarivista.it/articoli/la-disoccupazione-ai-tempi-del-coronavirus/)
        * [2020] [How to Use European Resources to Attract Talent to Italy (Italian)](https://www.fanpage.it/economia/come-utilizzare-le-risorse-europee-per-attrarre-talenti-in-italia/)
        * [2019] [Women and Work: What the State Does (and Does Not Do) (Italian)](https://www.econopoly.ilsole24ore.com/2019/03/08/donne-lavoro-stato/)
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
