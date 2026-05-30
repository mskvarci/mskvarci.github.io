---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: resume/
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle
        show: false
  - block: markdown
    id: research
    content:
      title: '🚀 Research'
      subtitle: ''
      text: |-
        **SSailOR — Spherical Sailing Omnidirectional Rover**
        *NC State University, Mechanical & Aerospace Engineering*

        I contributed CAD design work for a wind-propelled autonomous rover built for planetary surface exploration. The SSailOR uses adjustable sails for propulsion and directional control — eliminating the need for traditional power systems in remote, energy-scarce environments.

        My contributions: SolidWorks CAD modeling, iterative prototype development, and test model fabrication for wind tunnel validation — working alongside PhD researchers led by Aditya Varanwal in NCSU's aerospace program.

        📄 [Read the paper on arXiv →](https://arxiv.org/abs/2508.12443)
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
---
