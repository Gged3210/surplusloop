---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: SurplusLoop
      text: Transforming Surplus Into Opportunities
      # primary_action:
      #   text: Get Started
      #   url: https://hugoblox.com/templates/
      #   icon: rocket-launch
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
        color: "green"
        image:
          # Add your image background to `assets/media/`.
          filename: trees.jpg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            Assets
            repurposed
        - statistic: "100k+"
          description: |
            Total sales  
            since 2024
        - statistic: "3k+"
          description: |
            Trusted community  
            for support
    design:
      # Section background color (CSS class)
      # css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
        # padding: ["1rem", 0, "1rem", 0]
  # - block: features
  #   id: features
  #   content:
  #     title: Features
  #     text: Build your site with blocks 🧱
  #     items:
  #       - name: Optimized SEO
  #         icon: magnifying-glass
  #         description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
  #       - name: Fast
  #         icon: bolt
  #         description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
  #       - name: Easy
  #         icon: sparkles
  #         description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
  #       - name: No-Code
  #         icon: code-bracket
  #         description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
  #       - name: Highly Rated
  #         icon: star
  #         description: Rated 5-stars by the community.
  #       - name: Swappable Blocks
  #         icon: rectangle-group
  #         description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Who We Are
          # text: 'As easy as 1, 2, 3!'
          feature_icon: check
          features:
            - "We renew your old assets"
            - "Maximum return via our marketplace"
            - "Almost zero effort from your end"
          image: sustainable.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Abdou"
          role: "Procurement Manager of Newell Road"
          # Upload image to `assets/media/` and reference the filename here
          image: "abdou.jpg"
          text: "Awesome work guys, we have been working with SurplusLoop for the past 1 year in repurposing our assets for other organizations"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  

        
  # - block: cta-card
  #   content:
  #     title: Build your future-proof website
  #     text: As easy as 1, 2, 3!
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
