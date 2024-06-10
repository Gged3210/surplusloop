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
        - statistic: "10+"
          description: |
            Surplus
            Categories
        - statistic: "1000+"
          description: |
            Surplus
            Items
        - statistic: "100+"
          description: |
            Sellers/Buyers
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
          # text: Enabling circularity for surplus assets'
          feature_icon: bolt
          features:
            - "A B2B online marketplace for business surplus since April 2024"
            - "SurplusLoop provides a simple, fast and secure way to sell surplus online"
            - "Surplus ranging from overstock to idle assets to scrap to disposal items"
          image: about_us.jpg
        - title: Problems We Are Solving
          # text: We’re building a huge community of buyers and sellers
          feature_icon: check
          features:
            - "The secondary market today is fragmented and inefficient for disposal or procurement."
            - "Brokers make profits from “Buy Low Sell High” and result in a low return on surplus sold."
            - "The surplus in landfill causes environmental degradation and resource waste."
          image: problem.jpg
        - title: Our Solution
          # text: Flexible and seamless to get you the best price
          feature_icon: bolt
          features:
            - "Our AI-powered marketplace connects sellers to a large network of buyers from different industries and regions to sell their surplus assets online and get the best return."
            - "Our database algorithm matches buyers and sellers for quick sale."
            - "Our auction model ensures you get the best price on the market."
            - "Our escrow services give you more protection and buy with confidence."
          image: our_solution.jpg
        - title: What Makes SurplusLoop Unique?  
          # text: Flexible and seamless to get you the best price
          feature_icon: bolt
          features:
            - "Our marketplace aggregates the largest surplus supply and demand into one place."
            - "We are a one-stop shop for all surplus categories for disposal or procurement."
            - "Access surplus that is hard to find in the market."
          image: benefit.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Abdou"
  #         role: "CEO of ScaleIT"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "abdou.jpg"
  #         text: "Awesome work SurplusLoop, they've helped us gain 30% value across our asset liquidations"
  #       - name: "Michel Mustapha Ragio"
  #         role: "CFO of Newell Road"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "michel.jpg"
  #         text: "SurplusLoop is a great marketplace. I found great prices for used office equipment!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: [0, 0, 0, 0]
  
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
