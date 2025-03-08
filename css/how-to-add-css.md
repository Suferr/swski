---
description: browser HTML reads a style sheet
---

# How to add CSS

CSS styles HTML elements using three methods.

**Three Ways to Insert CSS**

1. **External CSS** – A separate `.css` file linked in HTML.
2. **Internal CSS** – Defined within the `<style>` tag in `<head>`.
3. **Inline CSS** – Added directly to an HTML element using `style` attribute.

**External CSS**

Best for managing styles across multiple pages.\
Example:

```html
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```

Example `styles.css` file:

```css
body {
  background-color: lightblue;
}
h1 {
  color: navy;
}
```

**Internal CSS**

Used for a single-page unique style.\
Example:

```html
<head>
  <style>
    body { background-color: linen; }
    h1 { color: maroon; margin-left: 40px; }
  </style>
</head>
```

**Inline CSS**

Styles a single element directly.\
Example:

```html
<h1 style="color:blue;">This is a heading</h1>
```

**Note:** Use inline styles sparingly.

**Multiple Stylesheets & Cascading Order**

When multiple styles apply, CSS follows this order of priority:

1. Inline styles
2. Internal & external styles (last one overrides previous ones)
3. Browser default styles

Example of cascading order:

```html
<head>
  <link rel="stylesheet" href="styles.css">
  <style>
    h1 { color: orange; } /* Overrides external CSS */
  </style>
</head>
```

CSS applies the last declared style when conflicts occur.
