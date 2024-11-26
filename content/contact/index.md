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
      autolink: true
      form:
        provider: netlify
        netlify:
          captcha: true
        form_name: 'Contact Form'
        action: '/thank-you/' # Redirect after form submission
        method: 'POST'
        fields:
          - name: name
            placeholder: Your Name
            type: text
            required: true
          - name: email
            placeholder: Your Email
            type: email
            required: true
          - name: message
            placeholder: Your Message
            type: textarea
            required: true
        submit_label: Send Message
        success_message: Thank you for contacting us! Redirecting...
        error_message: Oops! Something went wrong. Please try again.

    design:
      columns: '1'
      background:
        color: '#f9f9f9'
        text_color_light: false
      spacing:
        padding: ['20px', '20px', '20px', '20px']
---

### Create a "Thank You" Page

Add a new Markdown file for the thank-you page in your content directory:

```yaml
---
title: Thank You
date: 2022-10-24

type: default

sections:
  - block: markdown
    content:
      title: Thank You!
      text: |-
        We’ve received your message and will get back to you as soon as possible.  
        In the meantime, feel free to browse our [latest news](/news/) or [contact us](/contact/) again if needed.
    design:
      columns: '1'
      background:
        color: '#f9f9f9'
        text_color_light: false
      spacing:
        padding: ['50px', '20px', '50px', '20px']
---
