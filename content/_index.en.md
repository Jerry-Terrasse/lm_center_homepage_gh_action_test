---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-01-15
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: hero
    content:
      title: Igniting Minds to Shape New Worlds!
      primary_text: Large Model Research Center, School of Computer Science, Nanjing University
      secondary_text: The Research Center conducts innovative studies on large model system architectures, learning algorithms, and domain applications, delivering core technologies for Artificial General Intelligence (AGI) and Super Intelligence. Key research areas include chip, network, and computational system architectures for large models, efficient machine learning algorithms, knowledge-enhanced learning algorithms, as well as vision, language, multimodal, scientific, embodied large models, and intelligent agent systems.
      primary_action:
        text: Join Us
        url: /research
        icon: user-group
      secondary_action:
        text: Publications
        url: /publication
      announcement:
        text: "5 papers are accepted by CVPR 2025."
        link:
          text: "More"
          url: "/#news"
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
          filename: hero-bg.jpg
          filters:
            brightness: 0.5
  # - block: markdown
  #   content:
  #     title: '📚 Our Vision'
  #     subtitle: ''
  #     text: |-
  #       Human can integrate auditory sense, visual sense, and tactile sense in environment perception, and improve the abilities of understand and reforming environment by continuous learning and practice. Currently, computer has the primary auditory sense and visual sense, and its storage and processing abilities are constantly improved. However, computer is still inferior to human in environment perception, and the corresponding processing technology requires long-term development. Multimedia computing group (MCG) aims to study environment perception technology and use it in real applications. We hope to improve the perception ability and leverage the cognitive level of computer, and assist human to understand and reform the world.

  #     # Environment perception research requires the integration of various techniques, including multimedia content classification and processing, machine learning, modeling and visualization, intelligent interaction and big data processing. Currently, our research mainly involves: stereo visual media processing, object retrieval, scene modeling and processing, vision navigation, visual media retargeting, big data parallel processing, and large scale data visualization.
  #   design:
  #     columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      # page_type: post
      page_type: publication
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  # - block: collection
  #   id: events
  #   content:
  #     title: Events
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
