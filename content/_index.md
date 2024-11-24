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
      text: Collaborate, publish, and maintain technical knowledge with an all-in-one documentation site. Used by 100,000+ startups, enterprises, and researchers.
      items:
        - name: Optimized SEO
          icon: magnifying-glass
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Fast
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Easy
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: No-Code
          icon: code-bracket
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Highly Rated
          icon: star
          description: Rated 5-stars by the community.
        - name: Swappable Blocks
          icon: rectangle-group
          description: Build your pages with blocks - no coding required!
  - block: people
    content:
      title: About Us
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - About

---
