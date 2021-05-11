---
title: nurmaali
hide_title: true
sections:
  - section_id: hero
    type: section_hero
    title: 'Hi, this is my homepage'
    content: >-
      Welcome to my homepage. Here you can find what I do, my blog and how to contact me.
    actions:
      - label: Write me a message
        url: /contact
        style: button
  - section_id: latest-projects
    type: section_portfolio
    layout_style: mosaic
    title: Recent projects
    subtitle: Here's few of my projects
    projects_number: 4
    view_all_label: View All
    view_all_url: portfolio
  - section_id: services
    type: section_grid
    title: What I do
    subtitle: my activities and services
    col_number: two
    is_numbered: true
    grid_items:
      - title: University student
        content: >-
          I am studying at FIT CTU. My particular interests are web development and
          software engineering. I am primarily on the backend services but have
          quite a good grasp on the frontend too.
      - title: Developer
        content: >-
          I develop websites and automation tools. I am very interested in IoT (Internet of things).
          Prefer to work on backend but can do almost anything on frontend as well.
      - title: IoT
        content: >-
          Internet of Things is relatively new branch in computer science which I
          really like. I also have some experience working with Arduino.
      - title: Free time activities
        content: >-
          I like swimming and hiking. I read books especially focused on software
          development but I also love reading traditional literature and my favorite
          genre is science fiction.
  - section_id: testimonials
    type: section_testimonials
    title: Testimonials
    subtitle: People said about me
    col_number: three
    testimonials:
      - author: Sean Salazar
        avatar: images/sean_salazar.jpg
        avatar_alt: Sean Salazar's photo
        content: >-
          We were very satisfied with Ali's work. He designed a REST API for our
          e-shop and still maintains it. Everything is up and running.
      - author: Aubrey Hoover
        avatar: images/aubrey_hoover.jpg
        avatar_alt: Aubrey Hoover's photo
        content: >-
          We offered a landing page for our services, everything was delivered
          on time and is working perfectly. Good work.
      - author: Deegan Wallace
        avatar: images/deegan_wallace.jpg
        avatar_alt: Deegan Wallace's photo
        content: >-
          Ali helped me to develop smart home utilities and now I can control my
          home lights and heating system with my phone.
  - section_id: latest-posts
    type: section_posts
    title: Latest from the Blog
    subtitle: An optional subtitle of the section
    posts_number: 3
    col_number: three
    actions:
      - label: View Blog
        url: blog
        style: button
seo:
  title: nurmaali
  description: The preview of the Exto theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: nurmaali
      keyName: property
    - name: 'og:description'
      value: The preview of the Exto theme
      keyName: property
    - name: 'og:image'
      value: images/exto_preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: nurmaali
    - name: 'twitter:description'
      value: The preview of the Exto theme
    - name: 'twitter:image'
      value: images/exto_preview.png
      relativeUrl: true
layout: advanced
---
