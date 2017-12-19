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
    <label for="name">Name: </label>
    <input type="text" id="name" name="name" placeholder="Your Name">
  </div>
  <div class="form-group">
    <label for="email">eMail: </label>
    <input type="email" id="email" name="_replyto" placeholder="Your Email">
  </div>
  <div class="form-group">
    <label for="message">Message: </label>
    <textarea id="message" class="form-control" id="textarea" name="message" style="height:200px"></textarea>
  </div>
  <div align="right" class="form-group">
    <input type="submit" value="Send">
  </div>
    <input type="text" name="_gotcha" style="display:none" />
</fieldset>
</form>
