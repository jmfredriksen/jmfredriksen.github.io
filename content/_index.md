---
title: John Martin Fredriksen, RD, MSc
date: 2022-10-24
design:
  spacing: 6rem
summary: ""
type: landing
sections:
  - block: resume-biography-3
    content:
        username: me
        text:
          |
            Welcome to my personal portfolio. I am a registered clinical dietitian working in haematology and transplantation at the Karolinska University Hospital in Stockholm, and in the prevention and treatment of obesity and chronic disease at Re-start.no.
            
            This site serves as a hub for my work, including scientific publications, media contributions, educational content, and ongoing reflections on clinical practice, nutrition science and methodology.
        button: {}
        headings:
          about: Bio
          interests: ""
    design:
        background:
          gradient_mesh:
            enable: true
        name:
          size: md
        avatar:
          size: medium
          shape: circle
    id: bio
  - block: collection
    content:
        title: Selected publications
        text: ""
        filters:
          folders:
            - publications
          exclude_featured: false
    design:
        view: citation
  - block: collection
    content:
        count: 3
        offset: 0
        sort_by: Date
        sort_ascending: false
        title: Selected projects
        text: ""
        filters:
          folders:
            - projects
    design:
        view: ""
        show_date: true
        show_read_more: true
  - block: collection
    content:
        count: 3
        offset: 0
        sort_by: Date
        sort_ascending: false
        title: Latest blog posts
        filters:
          folders:
            - blog
    design:
        show_date: true
        show_read_time: true
        fill_image: true
        show_read_more: true
  - block: contact-info
    content:
        title: Contact Me
        username: me
        show_form: true
        prospective:
          button: {}
    design: {}
    id: contact
---
