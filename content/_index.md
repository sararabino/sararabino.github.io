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
      background:
        filename: vigna_sfondo.webp # <-- DEVE essere qui il nome del tuo file BLURRED
        image_process:
          filters:
            brightness: 0.8
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

  # SEZIONE 4: POLICY - INTRO (Markdown - Testo introduttivo)
  - block: markdown
    id: policy
    content:
      title: "Policy" 
      text: |
        **Think-Tank Tortuga**
        I was part of the Think-Tank Tortuga. Tortuga is an Italian think-tank of
        Economics students and young researchers. We publish newspaper articles which focus on particular economic issues of current relevance, devoting particular attention to their policy implications.
        [Visit the official website](https://www.tortuga-econ.it/)
    design:
      columns: '1'

  # SEZIONE 5: POLICY - REPORTS (Collection - Box Visuali in due colonne)
  - block: collection
    id: reports
    content:
      title: '' 
      filters:
        folders:
          - reports # Preleva i report da content/reports/
        exclude_featured: false
      count: 5
    design:
      view: card # FIX: Cambiato in 'card' per supportare meglio le colonne
      columns: 2 # FIX: Questo ora dovrebbe funzionare
      
  # SEZIONE 6: POLICY - OTHER CONTRIBUTIONS (Markdown - Lista di link)
  - block: markdown
    id: policy-articles
    content:
      title: '' 
      text: |
        ### Some Other Contributions (all in Italian):

        * [2022] [If Minimum Wage Increases, So Do Undeclared Wages](https://www.informazionesenzafiltro.it/se-il-salario-minimo-aumenta-anche-gli-stipendi-in-nero)
        * [2022] [Working Poor: Italy Can't Count Them. Would Minimum Wage Help?](https://www.informazionesenzafiltro.it/working-poor-italia-salario-minimo)
        * [2022] [Not All Companies Can Afford the Minimum Wage](https://www.informazionesenzafiltro.it/non-tutte-le-imprese-possono-permettersi-il-salario-minimo)
        * [2020] [Unemployment in the Time of Coronavirus](https://www.pandorarivista.it/articoli/la-disoccupazione-ai-tempi-del-coronavirus/)
        * [2020] [How to Use European Resources to Attract Talent to Italy](https://www.fanpage.it/economia/come-utilizzare-le-risorse-europee-per-attrarre-talenti-in-italia/)
        * [2019] [Women and Work: What the State Does (and Does Not Do)](https://www.econopoly.ilsole24ore.com/2019/03/08/donne-lavoro-stato/)
    design:
      columns: '1'

  # SEZIONE 7: OTHER INTERESTS
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

forzare la disposizione a due colonne.
