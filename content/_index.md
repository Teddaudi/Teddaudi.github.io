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
      title: About Us
      text: Collaborate, publish, and maintain technical knowledge with an all-in-one documentation site. Used by 100,000+ startups, enterprises, and researchers.
      items:
        - name: Optimized SEO
          icon: magnifying-glass
          style: "h-3 w-3 cursor-pointer text-blue-500 hover:text-blue-700 pb-2 pt-2"
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Fast
          icon: bolt
          style: "h-3 w-3 cursor-pointer text-yellow-500 hover:text-yellow-700 pb-2 pt-2"
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Easy
          icon: sun
          style: "h-3 w-3 cursor-pointer text-green-500 hover:text-green-700 pb-2 pt-2"
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: No-Code
          icon: code
          style: "h-3 w-3 cursor-pointer text-gray-500 hover:text-gray-700 pb-2 pt-2"
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Highly Rated
          icon: star
          style: "h-3 w-3 cursor-pointer text-purple-500 hover:text-purple-700 pb-2 pt-2"
          description: Rated 5-stars by the community.
        - name: Swappable Blocks
          icon: cubes
          style: "h-3 w-3 cursor-pointer text-red-500 hover:text-red-700 pb-2 pt-2"
          description: Build your pages with blocks - no coding required!

---
