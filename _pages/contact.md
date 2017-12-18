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

<form method="POST" action="https://api.staticman.net/v2/entry/eduardoboucas/staticman/gh-pages/comments">
  <input name="options[redirect]" type="hidden" value="https://my-site.com">
  <!-- e.g. "2016-01-02-this-is-a-post" -->
  <input name="options[slug]" type="hidden" value="{{ page.slug }}">
  <label><input name="fields[name]" type="text">Name</label>
  <label><input name="fields[email]" type="email">E-mail</label>
  <label><textarea name="fields[message]"></textarea>Message</label>
  
  <button type="submit">Go!</button>
</form>