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
        I am a Software Engineering student at Horizon School of Digital Technologies in Sousse, Tunisia, focused on full-stack web development and application security.

        I build web applications end to end, using React and TypeScript on the front end, Node.js and Express on the back end, and PostgreSQL or MongoDB for data. I pay close attention to application security from the ground up, implementing RS256 JWT authentication, role-based access control, and API hardening.

        In 2026, I worked as a full-stack developer intern architecting the official bilingual web platform for the TUNCIS 2026 international AI conference, and as a remote web developer intern at Instar building bilingual web solutions for King Word in Dubai.

        Outside of coding, I am an active IEEE member currently petitioning to establish an IEEE Student Branch at Horizon School of Digital Technologies, and an active organizer with Google Developer Groups (GDG).

        Looking ahead, I am eager to pursue international opportunities, complete my Master's studies in Germany, and continue building reliable software systems.
    design:
      columns: '1'
---
