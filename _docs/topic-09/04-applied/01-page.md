---
title: Comments in CSS
module: topic-09
permalink: /topic-09/css-comments/
---

<div class="divider-heading"></div>

As with your HTML work, you should get in the habit of including comments in your CSS code.

These comments can be used to tell you what you are trying to do, leave yourself notes about what is happening and why, or be used to inform your instructors about what you were attempting.

In CSS, comments are placed inside a 'forward-slash' and 'star' set (`/*...*/`).


<div class="code-heading">
  <span class="css">CSS</span>
</div>

```css
/* Everything between the forward-slash-star pair is a comment. */

/*
Comments in CSS are known as “block-comments”,
which means they can span multiple lines.

Notice how the comment delineators are placed on
lines above and below the text, respectively.
*/
```


### Leaving Notes:

This is the type syntax for comments in CSS regardless of whether your CSS is being written in a separate CSS document, as the above example implies, or within a style element in an HTML document.

<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
<!DOCTYPE html>
<html>
    <head>
        <!-- This is an HTML Comment.  -->
        <!-- Including this style of comment in CSS would raise an error. -->

        /* This is a CSS comment. */
        /* Notice it does not color correctly. */

        <style>
            /* This is a comment in CSS. */
            /* This syntax is only valid inside CSS. */
            /* This type of comment would cause an error in HTML. */

            <!-- This is an HTML Comment. -->
            <!-- Notice it does not color correctly. -->
        </style>

    </head>
</html>
```
