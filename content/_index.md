---
# Leave the homepage title empty to use the site title
title: ''
summary: "Population genomics | Invasive species evolution | Conservation | PhD @ Cornell"
date: 2026-05-26
type: landing

design:
  # Section spacing
  spacing: 1rem

sections:
  # ---------------------------------------------------------------------------
  # 1. Biography  (photo + name + role + bio + education + interests)
  #    Pulls structured data from data/authors/me.yaml
  #    Photo:  assets/media/authors/me.jpg
  # ---------------------------------------------------------------------------
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/Azwad-Iqbal-CV.pdf
      headings:
        about: ''
        education: Education
        interests: Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  # ---------------------------------------------------------------------------
  # 2. About  (your existing written content — preserved verbatim)
  # ---------------------------------------------------------------------------
  - block: markdown
    content:
      title: About
      text: |
        I am a broadly trained **population geneticist** and **evolutionary biologist** with a background in molecular ecology. I've worked with [large mammalian herbivores](https://www.pnas.org/doi/10.1073/pnas.2204400119) in African savannas, [yellow-fever mosquitoes](https://www.nature.com/articles/s41586-022-04675-4), and am currently working with American shad (*Alosa sapidissima*) at Cornell University.

        I am passionate about using genomics for conservation and have collaborated with stakeholders to guide my research.

        Outside of research, I am a competitive [powerlifter](https://www.openpowerlifting.org/u/azwadiqbal) and I enjoy playing video games, listening to music (hip hop, indie, electronic), and [producing mixes](https://soundcloud.com/wadzmix) for bhangra teams.

        ![Fieldwork in Malawi](me_2.png)
    id: about

  # ---------------------------------------------------------------------------
  # 3. Skills & Methods  (your existing features block — preserved verbatim)
  # ---------------------------------------------------------------------------
  - block: resume-skills
    content:
      title: Skills & Methods
      username: me
      items:
        - name: Programming
          description: 'R, Python, Bash, Snakemake'
          icon: devicon/python
        - name: Genomics
          description: 'Whole-genome sequencing, linked-read technologies, Haplotagging'
          icon: hero/swatch
        - name: Lab/Field
          description: 'Molecular ecology, museum samples, demography, DNA metabarcoding'
          icon: hero/book-open
    id: skills

  # ---------------------------------------------------------------------------
  # 4. Featured publication(s)  →  content/publications/ with featured: true
  # ---------------------------------------------------------------------------
  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: card
      columns: 1
    id: featured-publications

  # ---------------------------------------------------------------------------
  # 5. All publications  (citation view)  →  content/publications/
  # ---------------------------------------------------------------------------
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation
    id: publications

  # ---------------------------------------------------------------------------
  # 6. Research projects  →  content/projects/  (renders once you add projects)
  # ---------------------------------------------------------------------------
  - block: collection
    content:
      title: Research Projects
      text: Recent and ongoing research projects.
      filters:
        folders:
          - projects
      count: 3
    design:
      view: card
      columns: 3
    id: projects

  # ---------------------------------------------------------------------------
  # 7. Contact  (your existing written content — preserved verbatim)
  # ---------------------------------------------------------------------------
  - block: markdown
    content:
      title: Contact
      text: '**Ready to collaborate or have questions?** [Email me](mailto:ari22@cornell.edu)'
    design:
      background:
        color:
          dark: '#212529'
    id: contact
---