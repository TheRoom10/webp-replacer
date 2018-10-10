# Webp replacer
A simple JS script for replace a .webp image for a .png version in browsers that not support .webp format.

## Getting Started
You need to link JS file in  **bottom** of your HTML file.

```html
<script src="https://cdn.jsdelivr.net/gh/TheRoom10/webp-replacer@1.0/webp-replacer.js"></script>
```

Then add **data-webp** attribute with the URL of fallback img (.png, .jpg, .gif, etc.) for example:

```html
<img data-webp="example-img.jpg" src="example-img.webp">
```

