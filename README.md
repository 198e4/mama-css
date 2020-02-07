# Mama CSS

A simple and style independent CSS grid layout framework to build awesome user interfaces atop. Mama CSS provides no asthetic properties, your branding is up to you. Mama CSS gives you the bones, what your UI develops into from there is entirely up to you.

Why does the world need yet another framework? To seperate the layout and your brand.

## Features

### Style Independence

Style independence reduces the amount of framework overriding and the **C**ascading **S**hit **S**how that can happen when your bespoke code doesn't play nice with a framework's look and feel. Why fight your framework? 

### Flexible Naming Convention

A flexible naming convention for CSS classes lets you decide on how you'd prefer to name things. A secondary benefit of the naming convention is that it can be more forgiving of simple typos. Do your clients care that you forgot to use a hyphen, nope! Forget that hyphen and ship more code! 

Using an example class for a single column desktop layout (`d1c`) you can see how class names can be expressed using any of the following five styles:

|Naming Convention Style  | Example   |
|-------------------------|-----------|
|No Space                 |.d1c       |
|Single Hyphen            |.d-1c      |
|Double Hyphens           |.d--1c     |
|Single Underscore        |.d_1c      |
|Double Underscores       |.d__1c     |

### Parental Controls

With Mama CSS, layouts are controlled by the parent `div`'s class names, refered to in the examples here as a grid declaration. Any child `<div>` tags inside this parent automatically become layout columns (thanks to CSS grid). Any child `<div>` tags that exceed what's declared in the parent `div`'s grid declaration will simply wrap.

## Layout Examples

### Example #1
A 12 column layout on desktop with three equally spaced content containers can be created like so:

```
<div class="d3c">
  <div> ... </div>
  <div> ... </div>
</div>
```

Note that in this example `d3c` could be replaced with `d-3c`, `d_3c`, `d--3c`, or `d__3c` for the same three column layout. 

### Example #2
Building off of the first example, for a 3 column desktop layout, 2 column tablet layout, and a 1 column mobile layout, your underlaying grid would look something like this:

```
<div class="d3c t2c m1c">
  <div> ... </div>
  <div> ... </div>
</div>
```

## Layout Classes

### 12 Column Layouts (Equally Spaced)

Quickly create a CSS grid layout with up to 12 equally spaced columns for desktop, tablet and mobile.

|Layout Type        | Desktop (>=1301px)  | Tablet (<=1300px and >=701px) | Mobile (<=700px)  |
|-------------------|---------------------|-------------------------------|-------------------|
|1 Columns          | .d1c                | .t1c                          | .m1c              |
|2 Columns          | .d2c                | .t2c                          | .m2c              |
|3 Columns          | .d3c                | .t3c                          | .m3c              |
|4 Columns          | .d4c                | .t4c                          | .m4c              |
|5 Columns          | .d5c                | .t5c                          | .m5c              |
|6 Columns          | .d6c                | .t6c                          | .m6c              |
|7 Columns          | .d7c                | .t7c                          | .m7c              |
|8 Columns          | .d8c                | .t8c                          | .m8c              |
|9 Columns          | .d9c                | .t9c                          | .m9c              |
|10 Columns         | .d10c               | .t10c                         | .m10c             |
|11 Columns         | .d11c               | .t11c                         | .m11c             |
|12 Columns         | .d12c               | .t12c                         | .m12c             |

### Side Bar + 12 Column Grid Layouts

#### Left Sidebar Layouts

{{Topic Coming Soon}}

#### Right Sidebar Layouts

{{Topic Coming Soon}}

## Desktop, Tablet and Mobile Breakpoints

Mama CSS keeps layouts to three breakpoints. <700px for mobile, <1300px for tablets, and >1301px for desktops.

|Device Type            | Desktop   | Tablet                | Mobile  |
|-----------------------|-----------|-----------------------|---------|
|Breakpoint             |           |1300px                 |700px    |
|Viewport Width         |>=1301px   |<=1300px and >=701px   |<=700px  |

## Browser Support

Mama CSS is built using the CSS grid specification. Refer to [caniuse.com](https://caniuse.com/#feat=css-grid) for a CSS grid browser support matrix and browser specific notes.

## Attribution and Licensing

Mama CSS was created by Tyler Richardson. Mama CSS is available under the {{License Coming Soon}} license.
