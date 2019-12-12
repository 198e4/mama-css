# MamaCSS

A simple and style independent CSS grid layout framework to build awesome user interfaces atop.

## Layouts

Use Mama CSS to create the underlaying layout of your UI. With Mama CSS being styled independent it reduces the amount of framework overriding and framework/custom code friction on you the developer. A flexible naming convention for CSS classes also lets you decide on how you'de prefer to name things. For instance a 12 column grid with two equally spaced content containers can be created like so:

```
<div class="d2c"> <!-- Grid Declaration -->
  <div> ... </div> <!-- Column #1 -->
  <div> ... </div> <!-- Column #2 -->
</div>
```

With the Mama CSS framework, layouts are controlled with the a parent div's class name, refered to in the examples here as a "grid declaration". Any child `<div>` tags inside this parent automatically become layout columns (thanks to CSS grid). Any child `<div>` tags that exceed what's declared in the parent div's grid declaration will simply wrap.

### 12 Column Grid

{{Topic Coming Soon}}

### Side Bar + 12 Column Grid

{{Topic Coming Soon}}

### Desktop, Tablet and Mobile Breakpoints

{{Topic Coming Soon}}

## Browser Support

Mama CSS is built using the CSS grid specification. Refer to [caniuse.com](https://caniuse.com/#feat=css-grid) for a CSS grid browser support matrix and browser specific notes.

## Attribution and Licensing

Mama CSS was created by Tyler Richardson. Mama CSS is available under the {{License Coming Soon}} license.
