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

### Desktop, Tablet and Mobile Breakpoints

{{Topic Coming Soon}}

### 12 Column Grid

Quickly create a CSS grid layout with up to 12 columns for desktop, tablet and mobile.

|Layout Type        | Desktop (1301px)| Tablet (<=1300px and >=701px) | Mobile (<=700px)  |
|-------------------|-----------------|-------------------------------|-------------------|
|1 Columns          | .d1c            | .t1c                          | .m1c              |
|2 Columns          | .d2c            | .t2c                          | .m2c              |
|3 Columns          | .d3c            | .t3c                          | .m3c              |
|4 Columns          | .d4c            | .t4c                          | .m4c              |
|5 Columns          | .d5c            | .t5c                          | .m5c              |
|6 Columns          | .d6c            | .t6c                          | .m6c              |
|7 Columns          | .d7c            | .t7c                          | .m7c              |
|8 Columns          | .d8c            | .t8c                          | .m8c              |
|9 Columns          | .d9c            | .t9c                          | .m9c              |
|10 Columns         | .d10c           | .t10c                         | .m10c             |
|11 Columns         | .d11c           | .t11c                         | .m11c             |
|12 Columns         | .d12c           | .t12c                         | .m12c             |

#### Alternate Class Names

CSS class names used to declare desktop, tablet, and mobile layouts employ a flexible naming convention allowing you to choose a style that fits best for your project. Class names can be expressed using any of the five naming conventions listed in the example below


##### Example
Using the desktop 6 column layout class (.d6c) mentioned above as an example:

+ .d6c    
+ .d-6c   
+ .d--6c  
+ .d_6c   
+ .d__6c 


### Side Bar + 12 Column Grid

{{Topic Coming Soon}}

## Browser Support

Mama CSS is built using the CSS grid specification. Refer to [caniuse.com](https://caniuse.com/#feat=css-grid) for a CSS grid browser support matrix and browser specific notes.

## Attribution and Licensing

Mama CSS was created by Tyler Richardson. Mama CSS is available under the {{License Coming Soon}} license.
