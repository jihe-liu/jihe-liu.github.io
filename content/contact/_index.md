---
title: ""
type: page
---

## Get in Touch

If you have any questions, collaborations, or opportunities, feel free to contact me using the form below.

<style>
.contact-form {
  max-width: 600px;
  margin: 2rem auto;
  padding: 2rem;
  background: #f9f9f9;
  border-radius: 12px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
.contact-form label {
  font-weight: 600;
  margin-bottom: 0.5rem;
  display: block;
}
.contact-form input,
.contact-form textarea {
  width: 100%;
  border: 1px solid #ccc;
  border-radius: 8px;
  padding: 0.75rem;
  margin-bottom: 1rem;
  font-size: 1rem;
  box-sizing: border-box;
}
.contact-form button {
  display: block;
  width: 100%;
  background-color: #333;
  color: #fff;
  border: none;
  border-radius: 8px;
  padding: 0.75rem;
  font-size: 1.1rem;
  font-weight: bold;
  cursor: pointer;
  transition: background-color 0.3s ease;
}
.contact-form button:hover {
  background-color: #555;
}
</style>

<form action="https://formspree.io/f/mjkedvbg" method="POST" class="contact-form">
  <input type="hidden" name="_next" value="https://jihe-liu.github.io/thank-you/">

  <div>
    <label for="name">Your Name</label>
    <input id="name" type="text" name="name" required>
  </div>

  <div>
    <label for="email">Your Email</label>
    <input id="email" type="email" name="_replyto" required>
  </div>

  <div>
    <label for="subject">Subject</label>
    <input id="subject" type="text" name="subject">
  </div>

  <div>
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" required></textarea>
  </div>

  <button type="submit">Send</button>
</form>