---
title: "John Martin Fredriksen, RD, MSc"
summary: ""
date: "2022-10-24"
type: "landing"
design:
  spacing: "6rem"
sections:
  - block: "resume-biography-3"
    content:
      username: "me"
      text: |-
        Welcome to my personal portfolio. I am a registered clinical dietitian working in haematology and transplantation at the Karolinska University Hospital in Stockholm, and in the prevention and treatment of obesity and chronic disease at Re-start.no.

        This site serves as a hub for my work, including articles, media contributions, educational content, and ongoing reflections on clinical practice, nutrition science and methodology.
      button: {}
      headings:
        about: "Bio"
        interests: ""
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: "md"
      avatar:
        size: "medium"
        shape: "circle"
    ce: "section-bio"
    id: "bio"
    As: "section-f6aa0388"
  - block: "collection"
    content:
      title: "Selected publications"
      text: ""
      filters:
        folders:
          - "publications"
        exclude_featured: false
    design:
      view: "citation"
    ce: "section-2c6915a6"
    As: "section-8ef231ef"
  - block: "collection"
    content:
      count: 4
      offset: 0
      sort_by: "Date"
      sort_ascending: false
      title: "Selected projects"
      text: ""
      filters:
        folders:
          - "projects"
    design:
      view: "article-grid"
      show_date: true
      show_read_more: true
      fill_image: true
      show_read_time: false
    ce: "section-5f45e806"
    As: "section-e701992b"
  - block: "contact-info"
    content:
      title: "Contact Me"
      username: "me"
      show_form: true
      prospective:
        button: {}
    design: {}
    ce: "section-contact"
    id: "contact"
    As: "section-3de6d01e"
---
