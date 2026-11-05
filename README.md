# Capsule.css

Capsule.css supplies a small layout and styling foundation for a website or prototype. Its responsive layout classes, spacing helpers, and basic component styles let you compose pages without writing every layout rule from scratch.

It is useful for projects that need a CSS starting point without adopting a JavaScript UI framework. Include the stylesheet, apply the layout classes, and use the demo to explore combinations. Readable and minified distribution files are included for inspection and direct use.

## Get started

Copy a stylesheet from [dist](dist) into your project and include it in the page:

```html
<link rel="stylesheet" href="dist/capsule.min.b0.2.css">
```

```html
<div class="capsule">
  <div class="row gap:8 padding:5">
    <div class="box:6">First column</div>
    <div class="box:6">Second column</div>
  </div>
</div>
```

## Examples

Open [demo/index.html](demo/index.html) to explore the layout classes and components. The distribution includes readable and minified CSS; no JavaScript framework is required.

[MIT license](LICENSE)
