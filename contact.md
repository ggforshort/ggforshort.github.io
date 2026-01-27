---
title: Contact
layout: default
---
Please get in touch using the form below. Thank you!

<form
  action="https://formspree.io/f/xwvozzjy"
  method="POST"
>
  <label>
    Your name:<br>
    <input type="text" name="name" required>
  </label><br>
  <label>
    Your email address:<br>
    <input type="email" name="email" required>
  </label><br>
  <label>
    Your message:<br>
    <textarea name="message" required></textarea>
  </label><br>
  <button type="submit">Submit</button>
</form>

<script>
window.onbeforeunload = () => {
  for(const form of document.getElementsByTagName('form')) {
    form.reset();
  }
}
</script>
