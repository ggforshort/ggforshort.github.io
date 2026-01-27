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
    Your name<span style="color:red">&ast;</span><br>
    <input type="text" name="name" required>
  </label><br>
  <label>
    Your email address<span style="color:red">&ast;</span><br>
    <input type="email" name="email" required>
  </label><br>
  <label>
    Your message<span style="color:red">&ast;</span><br>
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
