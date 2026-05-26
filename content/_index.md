---
title: "Azwad Iqbal – Population Geneticist & Evolutionary Biologist"
summary: "Population genomics | Invasive species evolution | Conservation | PhD @ Cornell"
date: 2026-05-26
design:
  spacing: 6rem
type: landing
sections:
  - block: hero
    content:
        title: Azwad Iqbal
        text: "Population geneticist & evolutionary biologist at Cornell. Studying rapid evolution with population genomics and conservation applications."
        primary_action:
          text: View CV
          url: "https://raw.githubusercontent.com/azwadriqbal/azwadriqbal.github.io/refs/heads/main/cv/Azwad-Iqbal-CV.pdf"
        secondary_action:
          text: Contact
          url: "#contact"
        announcement:
          text: Now accepting collaborations
    design:
        background:
          color:
            dark: "#10151A"
        text_color_light: true
        image:
          filename: azwad.jpg
  - block: markdown
    content:
        title: About
        text:
          |
            I am a broadly trained **population geneticist** and **evolutionary biologist** with a background in molecular ecology. I've worked with [large mammalian herbivores](https://www.pnas.org/doi/10.1073/pnas.2204400119) in African savannas, [yellow-fever mosquitoes](https://www.nature.com/articles/s41586-022-04675-4), and am currently working with American shad (*Alosa sapidissima*) at Cornell University.
            
            I'm passionate about using genomics for conservation and have collaborated with stakeholders to guide my research.
            
            Outside research: powerlifting, video games, music (hip hop, indie, electronic), and [producing mixes](https://soundcloud.com/wadzmix) for bhangra teams.
    id: about
  - block: features
    content:
        title: "Skills & Methods"
        items:
          - name: Programming
            description: "R, Python, Bash, Snakemake"
            icon: devicon/python
          - name: Genomics
            description: "Whole-genome sequencing, linked-read technologies, Haplotagging"
            icon: hero/swatch
          - name: Lab/Field
            description: "Molecular ecology, museum samples, demography, DNA metabarcoding"
            icon: hero/book-open
    id: skills
  - block: collection
    content:
        title: Research Projects
        text: Recent and ongoing research projects.
        page_type: project
        count: 3
        sort_by: Date
    design:
        view: card
        columns: 3
    id: projects
  - block: collection
    content:
        title: Experience
        text: Academic and research experience.
        page_type: resume-experience
        count: 3
        sort_by: Date
    design:
        view: date-title-summary
    id: experience
  - block: collection
    content:
        title: Education
        text: Degrees and honors.
        page_type: resume-awards
        count: 2
        sort_by: Date
    design:
        view: date-title-summary
    id: education
  - block: markdown
    content:
        title: Contact
        text: "**Ready to collaborate or have questions?** [Mail me](mailto:ari22@cornell.edu)"
    design:
        background:
          color:
            dark: "#212529"
    id: contact
---
