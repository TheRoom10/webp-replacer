# Webp replacer
A simple JS script for replace a .webp image for a .png version in unsupported browsers.

## Getting Started
You need to link JS file in  **bottom** of your HTML file.

```html
<script src="webp-replacer.js"></script>
```

Then add **data-webp** attribute with the URL of fallback img (.png, .jpg, .gif, etc.) for example:

```html
<img src="example-img.jpg" data-webp="example-img.webp">
```

