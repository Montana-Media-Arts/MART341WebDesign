---
title: Pseudo-Elements
module: topic-10
permalink: /topic-10/pseudo-elements/
---

<div class="divider-heading"></div>

The first type of pseudo-style we will discuss is **pseudo-elements**.

There are two types of pseudo-elements:
- `::first-letter`
- `::first-line`

Respectively, these allow for the selection of the first letter or first line in an element's text. This selection can then be used to alter the appearance or display of _just_ the first letter or line.

<div class="code-heading">
  <span class="css">CSS</span>
</div>

```css
selector::first-letter {}
selector::first-line {}

/* The word selector in the above is replaced with
the normal CSS selectors used to identify elements. */
p::first-letter {
  color: green;
}
```

### “Why would I use a pseudo-element?”

In the example below, try changing the font size. Because we used pseudo-selectors instead of more direct selectors, content like the first line remains styled as set. The first line remains the first line, despite how many words there are in it.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="abZpXYo" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="OZMdWz" class="codepen"></p>
</div>
