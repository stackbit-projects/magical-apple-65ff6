---
title: Home
hide_title: true
sections:
  - type: section_hero
    template: section_hero
    title: 'Hi, I''m Ahmed'
    section_id: hero
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
    actions:
      - type: action
        template: action
        label: Let's talk
        url: /contact
        style: button
  - type: section_portfolio
    template: section_portfolio
    title: Recent Work
    section_id: latest-projects
    subtitle: An optional subtitle of the section
    layout_style: mosaic
    projects_number: 6
    view_all_label: View All
    view_all_url: portfolio
  - type: section_testimonials
    template: section_testimonials
    title: Testimonials
    section_id: testimonials
    subtitle: An optional subtitle of the section
    col_number: three
    testimonials:
      - type: testimonial
        template: testimonial
        author: Sean Salazar
        avatar: images/sean_salazar.jpg
        avatar_alt: Sean Salazar's photo
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla.
      - type: testimonial
        template: testimonial
        author: Aubrey Hoover
        avatar: images/aubrey_hoover.jpg
        avatar_alt: Aubrey Hoover's photo
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - type: testimonial
        template: testimonial
        author: Deegan Wallace
        avatar: images/deegan_wallace.jpg
        avatar_alt: Deegan Wallace's photo
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam.
  - type: section_posts
    template: section_posts
    title: Latest from the Blog
    section_id: latest-posts
    subtitle: An optional subtitle of the section
    posts_number: 3
    col_number: three
    actions:
      - type: action
        template: action
        label: View Blog
        url: blog
        style: button
layout: advanced
---
