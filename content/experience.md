---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

sections:
  # Teaching Section
  - block: resume-experience
    content:
      username: admin
      category: Teaching      # Mostra solo le voci Teaching
    design:
      date_format: 'January 2006'
      is_education_first: false
      section_title: "Teaching"  # Questo apparirà come titolo grande

  # Other Experience Section
  - block: resume-experience
    content:
      username: admin
      exclude_category: Teaching  # Mostra tutte le voci tranne Teaching
    design:
      date_format: 'January 2006'
      is_education_first: false
      section_title: "Other Experience"

  - block: resume-skills
    content:
      title: Skills
      username: admin
    design:
      show_skill_percentage: false

  - block: resume-awards
    content:
      title: Awards
      username: admin

  - block: resume-languages
    content:
      title: Languages
      username: admin
---
