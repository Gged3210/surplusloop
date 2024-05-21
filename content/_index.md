---
title: ''
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "0rem"

sections:
  - block: hero
    content:
      title: SurplusLoop
      text: Asset Liquidation Made Easy
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
        - statistic: "20%"
          description: |
            Surplus
            in organizations
        - statistic: "10%"
          description: |
            Spent on 
            asset storage
        - statistic: "15%"
          description: |
            Global waste 
            from surplus assets
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
        - title: About SurplusLoop
          text: Enabling circularity for surplus assets'
          feature_icon: bolt
          features:
            - "We’re passionate about creating a win-win for businesses and the planet"
            - "Our expertise and marketplace helps transform surplus assets into value-adds"
            - "We operate as partners, to deliver what you need with better results"
          image: about.jpg
        - title: We have you covered
          text: We’re building a huge community of buyers and sellers
          feature_icon: check
          features:
            - "For sellers, we help you liquidate and maximize your returns from surplus assets"
            - "For buyers, we give you access to assets in the secondary market at lower prices"
            - "We’re a one stop solution for seamless asset liquidation"
          image: benefit.jpg
        - title: Our Sales Solution
          text: Flexible and seamless to get you the best price
          feature_icon: bolt
          features:
            - "Our marketplace fuels your business by aggregating supply and demand"
            - "Our auction solutions allows the best market price to be achieved"
            - "Our direct sales solutions allows quick algorithmic matching between buyer and seller"
          image: solution.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Abdou"
          role: "CEO of ScaleIT"
          # Upload image to `assets/media/` and reference the filename here
          image: "abdou.jpg"
          text: "Awesome work SurplusLoop, they've helped us gain 30% value across our asset liquidations"
        - name: "Michel Mustapha Ragio"
          role: "CFO of Newell Road"
          # Upload image to `assets/media/` and reference the filename here
          image: "michel.jpg"
          text: "SurplusLoop is a great marketplace. I found great prices for used office equipment!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: [0, 0, 0, 0]
  
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
