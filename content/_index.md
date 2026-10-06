---
title: ''
summary: ''
date: 2026-10-05
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: media/CV.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: collection
    id: research
    content:
      title: Research
      subtitle: ''
      text: ''
      filters:
        folders:
          - publications
        publication_type: manuscript
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: imf
    content:
      title: IMF Work
      subtitle: Journal articles and working papers written with IMF colleagues.
      text: ''
      filters:
        folders:
          - publications
        exclude_publication_type: manuscript
    design:
      view: citation
  - block: markdown
    id: presentations
    content:
      title: Selected Presentations
      subtitle: ''
      text: |-
        **2025:** IMF Spring Meetings Analytical Corner; Midwest Macroeconomics Meeting (Federal Reserve Bank of Cleveland)

        **2023:** IMF; Boston Fed; Department of the Treasury; UIUC

        **2022:** Penn; WUSTL Economics Graduate Student Conference

        **2021:** Penn; St. Louis Fed; SED Annual Meeting; ESPE Annual Conference; Warwick Economics PhD Conference
    design:
      columns: '1'
---
