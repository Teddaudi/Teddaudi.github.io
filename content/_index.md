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

  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: 'Check out my recent blog posts below!'
      items:
        - title: "Exploring the Basics of Machine Learning"
          description: "A beginner's guide to understanding machine learning concepts."
          image: machine-learning.jpg
          link: /posts/machine-learning-basics/
        - title: "Top 10 JavaScript Tips"
          description: "Boost your JavaScript skills with these essential tips."
          image: javascript-tips.jpg
          link: /posts/javascript-tips/
        - title: "Building Scalable Web Applications"
          description: "Learn the best practices for building scalable applications."
          image: scalable-web-apps.jpg
          link: /posts/scalable-web-apps/
        - title: "Introduction to Cloud Computing"
          description: "Discover the key concepts of cloud computing."
          image: cloud-computing.jpg
          link: /posts/cloud-computing/
        - title: "Getting Started with React"
          description: "A guide to building dynamic user interfaces with React."
          image: react-intro.jpg
          link: /posts/react-intro/
        - title: "Understanding RESTful APIs"
          description: "Learn about designing and consuming RESTful APIs."
          image: restful-apis.jpg
          link: /posts/restful-apis/
        - title: "Mastering CSS Grid Layout"
          description: "Design responsive layouts with CSS Grid."
          image: css-grid.jpg
          link: /posts/css-grid/
        - title: "The Future of Artificial Intelligence"
          description: "Explore AI's potential impact on the world."
          image: future-of-ai.jpg
          link: /posts/future-of-ai/
        - title: "Version Control with Git"
          description: "An essential guide to mastering Git."
          image: git-guide.jpg
          link: /posts/git-guide/
    design:
      view: grid
      columns: 3
      item_layout:
        image_position: above
        title_position: below
        description_position: below
---
