---
layout: default
title: Contact
slug: /contact
---

# Contact Me

Want to get in contact with me? Send me a shout here, and we'll chat!

<style>
  .form-container { max-width: 100%; }
  .form-container input { position: relative; top: 0; left: 0; width: 100%; height: 20px; padding: 0 ; }
  .form-container textarea { position: relative; top: 0; left: 0; width: 100%; height: 80px; padding: 0; }
</style>
<form action="https://formspree.io/xyybobka" method="POST" class="form-container">
  <label>Name:</label><br />
  <input type="text" name="_name" />
  <label>Email:</label><br />
  <input type="text" name="_replyto" />
  <label>Subject:</label><br />
  <input type="text" name="_subject" />
  <label>Your message:</label><br />
  <textarea name="message"></textarea>
  <button type="submit">Send</button>
</form>
