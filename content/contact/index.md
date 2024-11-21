---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Get in Touch
      text: |-
        We’d love to hear from you! Whether you have a question, feedback, or just want to say hello, feel free to reach out using the contact details below or schedule an appointment with us.
      email: hello@example.org
      phone: '+1 888 888 8888'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2.
      office_hours:
        - 'Monday: 10:00 AM - 1:00 PM'
        - 'Wednesday: 9:00 AM - 10:00 AM'
      appointment_url: 'https://calendly.com'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        netlify:
          captcha: true # Enable CAPTCHA challenge to reduce spam
    design:
      columns: '1'
      background:
        color: '#f9f9f9'
        text_color_light: false
      spacing:
        padding: ['20px', '20px', '20px', '20px']

  - block: markdown
    content:
      title: Our Office
      subtitle: ''
      text: |-
        Come visit us at our headquarters, located in the heart of Stanford. Our friendly staff is ready to assist you during office hours. For a smoother experience, we recommend booking an appointment in advance.
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 0.9
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['50px', '20px', '50px', '20px']
---

