---
layout: default
title: Contact
permalink: /contact/
---

# Contact

<form action="https://formspree.io/f/xrbnwyaq" method="POST" class="contact-form">
  <label for="name">Name</label>
  <input id="name" type="text" name="name" required>

  <label for="email">Email</label>
  <input id="email" type="email" name="email" required>

  <label for="message">Message</label>
  <textarea id="message" name="message" rows="8" required></textarea>

  <!-- optional hidden subject -->
  <input type="hidden" name="_subject" value="New message from blog contact form">

  <button type="submit">Send</button>
</form>

