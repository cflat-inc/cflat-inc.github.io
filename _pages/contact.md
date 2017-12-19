---
title: Contact
permalink: /contact/
layout: splash
header:
  overlay_image: /assets/images/hd-home.jpg
  overlay_filter: 0.5
  caption: 'Photo credit: [**pixabay**](https://pixabay.com)'
published: true
---
<p></p>

<form class="form-horizontal" action="//formspree.io/{{site.contactEmail}}" method="POST">
<fieldset>
  <div class="form-group">
    <label for="contact_name">Name: </label>
    <input type="text" name="name" placeholder="Your Name">
  </div>
  <div class="form-group">
    <input type="email" name="_replyto" placeholder="Your Email">
  </div>
  <div class="form-group">
    <textarea class="form-control" id="textarea" name="message">Your Message</textarea>
  </div>
  <div class="form-group">
    <input type="submit" value="Send">
  </div>
    <input type="text" name="_gotcha" style="display:none" />
</fieldset>
</form>
