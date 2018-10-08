# simple-css-flex-grid

This is avery simple, small, tight grid system built in CSS. I've put it here more to keep it around for future work than to offer it as an open source project. However, if you wish to use it, please do.

The relevant HTML should be obvious, but I might create a demo page.


\[untested code follows\]

```
...

<div class="grid-container grid-half-and-quarters-width">
  <div>
    <p>This will be half width</p>
  </div>
  <div>
    <p>This will be quarter width<p>
  </div>
  <div>
    <p>This will be quarter width</p>
  </div>
</div>

<div class="grid-container grid-two-thirds-one-third-width">
  <div>
    <p>This will be two-thirds width</p>
  </div>
  <div>
    <p>This will be one third width<p>
  </div>
</div>

...
```

And done.

You can replace the divs with HTML5 semantic containers if you wish, the CSS will target any element.

Features:

 - Responsive at two breakpoints. At 1010px width all elements become 50% width. At 768px width all elements stack vertically.

 - Comes with a number of width definition classes, providing full, half, third and quarter widths for child elements, along with combinations.
 
 - Under 60 lines of CSS code.

 - Minimal impact on markup.
