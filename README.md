# Docsify Accordion

Small plugin to use accordions in your docsify documentations.

## Usage

1. Implement stylesheet + javascript into your document:

```html
<link rel="stylesheet" href="//unpkg.com/docsify-accordion/src/style.css">
<script src="//unpkg.com/docsify-accordion/src/index.js"></script>
```

2. Load plugin

```
window.$docsify = {
    plugins: [
      io_accordion,
      ...,
    ]
}
```

### Example FAQ Page

Starting your line with `+ ` and ending with ` +` (spaces are important) will convert the list into an accordion

```md

# FAQ Section

Introduction text for the FAQ page.

+ Question 1? +

  Answer 1

+ Question 2? +

  Answer 2

```
