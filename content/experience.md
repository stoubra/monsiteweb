---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: markdown
    content:
      title: Enseignement
      subtitle: ''
      text: |
        ### Nom du cours ou du module (2024 - Présent)
        **Établissement / Université** — Niveau (ex. Master 1)
        * Description courte des matières enseignées ou des travaux dirigés.

        ### Autre cours (2022 - 2024)
        **Établissement** — Niveau
        * Description courte.
    design:
      columns: '1'
  
 # - block: resume-skills
 #   content:
 #     title: Skills & Hobbies
 #     username: me
 # - block: resume-awards
 #   content:
 #     title: Awards
 #     username: me
 # - block: resume-languages
 #   content:
 #     title: Languages
 #     username: me
---
