---
title: ""
summary: "Wenkai Xing — Ph.D. student at Peking University working on programming languages, program verification, and LLM agents."
date: 2026-07-20
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ""
      headings:
        about: About Me
        education: Education
        interests: Research Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: rounded

  - block: markdown
    content:
      title: "Research"
      subtitle: "Programming Languages · Program Verification · LLM Agents"
      text: |-
        I work on topics at the intersection of programming languages and large language models, with a focus on LLM-assisted program verification and practical approaches that simplify reliable agent implementation.

        I am happy to discuss research ideas, collaborations, and open-source projects.
    design:
      columns: "1"

  - block: collection
    id: projects
    content:
      title: Featured Projects
      text: Healthcare, autonomous driving, and reliable AI agent systems.
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: true
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: true

  - block: collection
    id: publications
    content:
      title: Publications
      text: Selected research updates and publications.
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
