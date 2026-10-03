---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'About me'
      subtitle: ''
      text: |-
        I'm a Software Engineering student at Horizon School of Digital Technologies in Sousse, Tunisia, focused on full-stack development and application security.

        I build web applications end to end: React and TypeScript on the front end, Node.js and Express on the back end, with PostgreSQL or MongoDB underneath. I design security in from the start, with JWT authentication, role-based access control, and API hardening.

        In 2026 I worked on the official bilingual (EN/FR) web platform for the TUNCIS 2026 international AI conference, and as a remote web developer intern on bilingual (EN/AR) websites for a company based in Dubai.

        Beyond code, I'm a GDG organizer and an IEEE member, and I'm currently founding an IEEE Student Branch Horizon School Of Digital Technologies, with the petition in progress.

        What's next: I want to take on opportunities abroad, do my Master's in Germany, and learn from new cultures along the way.
    design:
      columns: '1'
---
