---
widget: contact
headless: true
active: true
weight: 50

title: Contact
subtitle: Get in touch

# Contact form fields
form:
  provider: netlify   # or formspree / email
  formspree:
    id: ""  # only if using Formspree
  netlify:
    # no extra config needed if site is deployed with Netlify
  fields:
    - name: "Name"
      type: "text"
      required: true
    - name: "Email"
      type: "email"
      required: true
    - name: "Subject"
      type: "text"
      required: false
    - name: "Message"
      type: "textarea"
      required: true
  submit:
    text: "Send"
---