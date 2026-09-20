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
    
/* ================= RESEARCH SECTION ================= */

/* the spans control all the spacing */
#research p { margin: 0; }

/* "Job Market Paper" / "Work in Progress" labels */
#research .res-label {
  display: block;
  font-size: 0.8rem;
  font-weight: 600;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: #6b7280;
  margin: 2rem 0 0.6rem;
  padding-bottom: 0.35rem;
  border-bottom: 1px solid #e5e7eb;
}
#research p:first-of-type .res-label { margin-top: 0; }

/* paper titles */
#research .paper-title {
  display: block;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 1.2rem;
  font-weight: 700;
  line-height: 1.35;
  color: #0f766e;
  margin-top: 1.1rem;
}

/* co-authors */
#research .paper-authors {
  display: block;
  font-size: 0.95rem;
  color: #4b5563;
}
#research .paper-authors a {
  color: inherit;
  text-decoration: underline;
  text-underline-offset: 2px;
}

# 🔄 SEZIONE 3: TEACHING (NUOVO LAYOUT CON ICONE)
- block: markdown
  id: teaching # ANCORA: /#teaching
  content:
    title: "Teaching" # Titolo esatto
    text: |
      **University of Zurich**
      
      {{< icon name="academic-cap" pack="hero" >}} **Lecturer** (The Economics of Gender Norms, BA), 2024
      
      {{< icon name="academic-cap" pack="hero" >}} **Teaching Assistant** (Econometrics for Research Students, PhD), 2023–2024
      
      <br>

      **Bocconi University** 
      
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
