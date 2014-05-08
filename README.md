dsv_drupal_theme
=================

DSV External Drupal theme based on Bootstrap


footer regions
--------------

This theme has two footer regions: left and right. This is in order to match the SU way of having contact info in the left part of the footer, and page-specific links (like "Contact, Jobs, etc.") on the right side.

<h3>setting up the footer regions</h3>
In order to utilize these (and make them look almost exactly like the ones at <a href="http://www.su.se">su.se</a>), create a block for each side of the footer and then place each of these code snippets in their appropriate footer block. The following piece of HTML (the blocks text area need to be set to "Full HTML" in Drupal, btw) is the default DSV one for the left footer section:

```html
<address>
  <strong>Institutionen för data- och systemvetenskap, DSV</strong>
  Stockholms universitet, DSV, Forum 100, 164 40 Kista | Telefon: 08-16 20 00
</address>
```

And the following is for the right side:
```html
<ul>
  <li><a href="http://www.su.se/om-oss/lediga-anst%C3%A4llningar">Lediga jobb</a></li>
  <li><a href="http://dsv.su.se/omdsv/kontakt">Kontakt</a></li>
</ul>
```
