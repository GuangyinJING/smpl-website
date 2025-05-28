---
title: Tour
date: 2025-05-28
type: landing
sections:
  - block: slider
    content:
      slides:
        - title: 👋 Welcome to the SMPL
          content: Here, we are trying to learn from **Living** machinery...
          align: center
          background:
            image:
              filename: coders.jpg
              filters:
                brightness: 0.7
            position: right
            color: "#666"
        - title: Swimming Bacteria - Microswimmer
          content: Just as Aristotle once pondered why humans swing their arms while walking, we wonder for what E. coli do wobble spontaneously as they swim.
          align: left
          background:
            image:
              filename: wobble.png
              filters:
                brightness: 0.7
            position: center
            color: "#555"
        - title: Swimming in Complex Environments
          content: Comlex fluids, versatile boundaries, confinements
          align: right
          background:
            image:
              filename: welcome.jpg
              filters:
                brightness: 0.5
            position: center
            color: "#333"
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Join Us
            url: ../contact/
    design:
      slide_height: ""
      is_fullscreen: true
      loop: false
      interval: 2000
  - block: collection
    content:
      title: Force sensing of bacterial flagella motor
      text: "How the bacteria sense the dynamic flows?"
      image:
      count: 5
      filters:
        folders:
          - publication
        publication_type: article
    design:
      view: citation
      columns: "1"     
  - block: collection
    content:
      title: Swimming gaits of growing bacteria
      text: "How the bacteria behave when subjected to flow, boundary and at different phenotype?"
      image:
      count: 5
      filters:
        folders:
          - publication
        publication_type: article
    design:
      view: citation
      columns: "1" 
  
---