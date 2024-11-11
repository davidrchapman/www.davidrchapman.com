---
title: Contact
---

Use the form below to send me a message:

<form method="post" action="https://formspree.io/f/mwkwnwjp">
  <input type="hidden" name="subject" value="Contact Form" />

  <label for="email">Your Email:</label><br />
  <input type="email" id="email" name="email" placeholder="name@domain.com" autofocus required /><br />

  <label for="name">Your Name:</label><br />
  <input type="text" id="name" name="name" placeholder="John Doe" maxlength="255" required /><br />

  <label for="message">Your Message:</label><br />
  <textarea id="message" name="message" placeholder="Enter your message here" maxlength="2048" required></textarea><br />

  <input type="hidden" name="_next" value="/success" />
  <input class="hidden" type="text" name="_gotcha" />
  <input type="hidden" name="_format" value="plain" />
  <button type="submit">Submit</button>
</form>
