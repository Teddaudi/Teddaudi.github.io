---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: 👋 Welcome to the group
          content: Take a look at what we're working on...
          align: center
          background:
            image:
              filename: coders.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: Lunch & Learn ☕️
          content: 'Share your knowledge with the group and explore exciting new topics together!'
          align: left
          background:
            image:
              filename: contact.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: World-Class Semiconductor Lab
          content: 'Just opened last month!'
          align: right
          background:
            image:
              filename: welcome.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Join Us
            url: ../contact/
    design:
      slide_height: ''
      is_fullscreen: true
      loop: false
      interval: 2000
  - block: features
  id: features
  content:
    title: Features
    text: "Collaborate, publish, and maintain technical knowledge with an all-in-one documentation site. Trusted by 100,000+ startups, enterprises, and researchers."
    items:
      - name: Optimized SEO
        icon: magnifying-glass
        style: "h-6 w-6 text-blue-500 hover:text-blue-700"
        description: "Effortless SEO with automatic sitemaps, RSS feeds, and rich metadata for better syndication."
      - name: Blazing Fast
        icon: bolt
        style: "h-6 w-6 text-yellow-500 hover:text-yellow-700"
        description: "Experience super-fast page loads with Tailwind CSS and lightning-quick site building using Hugo."
      - name: Effortless Setup
        icon: sparkles
        style: "h-6 w-6 text-green-500 hover:text-green-700"
        description: "Deploy to GitHub Pages with just one click. Get your website live in under 5 minutes!"
      - name: No-Code Editing
        icon: code-bracket
        style: "h-6 w-6 text-gray-500 hover:text-gray-700"
        description: "Design and update your site easily using Markdown and configurable YAML parameters."
      - name: Community Approved
        icon: star
        style: "h-6 w-6 text-purple-500 hover:text-purple-700"
        description: "Highly rated by users, with a 5-star community rating for performance and simplicity."
      - name: Modular Design
        icon: rectangle-group
        style: "h-6 w-6 text-red-500 hover:text-red-700"
        description: "Build stunning pages effortlessly with swappable blocks — no coding skills required."

  - block: people
    content:
      title: About Us
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - About

---
