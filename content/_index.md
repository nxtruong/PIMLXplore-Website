---
title: 'PIMLXplore'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: hero
    id: top
    content:
      title: Explore&nbsp;Physics&minus;Informed Machine&nbsp;Learning
      text: LEARNING RESOURCES. DATA SETS. OPEN-SOURCE CODE. PLAYGROUND.
      primary_action:
        text: Start Learning
        url: learn
        icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      # announcement:
      #   text: "Announcing the release of version 1."
      #   link:
      #     text: "Read more"
      #     url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: background.png
          filters:
            brightness: 0.38
  - block: features
    id: about
    content:
      title: About PIMLXplore
      text: |
        PIMLXplore is a web portal to physics-informed machine learning in science and engineering, funded by an NSF CAREER project.

        **Physics-informed machine learning (PIML)** is a set of methods and tools that systematically integrate machine learning algorithms with physical constraints and abstract mathematical models developed in scientific and engineering domains. As opposed to purely data-driven methods, PIML models can be trained with additional information obtained by enforcing physical laws such as energy and mass conservation, stability, or invariance.  The integration of machine learning and physics can yield *more effective, physically consistent, and data-efficient models*.
        
        PIMLXplore has the following main features / components.
      items:
        - name: Learning Resources
          icon: book-open
          description: Learn about PIML from tutorials, workshops, papers, and videos.
        - name: Data
          icon: document
          description: Public datasets for PIML research.
        - name: Software
          icon: code-bracket
          description: Programming libraries and software tools for PIML, code from papers.
        - name: Playground
          icon: play
          description: Learn and explore PIML interactively on the web.
  - block: markdown
    content:
      title: Meet the Team
      text: |
        - **[Prof. Truong X. Nghiem](https://truong.nxtlab.org/)**, Associate Professor, _Department of Electrical and Computer Engineering, University of Central Florida_.
        - **Dr. Binh Nguyen**, Postdoctoral Associate, _Department of Electrical and Computer Engineering, University of Central Florida_
        - **Nam Nguyen**, Ph.D. Student, _Department of Electrical and Computer Engineering, University of Central Florida_
  - block: markdown
    content:
      title: Funding
      text: |
        **PIMLXplore** is supported by the U.S. National Science Foundation through the CAREER Award [#2514584](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2514584). We gratefully acknowledge the NSF's support, which has been instrumental to our research and the development of this website.        
---
