# Where To

### The `<script>` Tag

JavaScript is placed inside `<script>` tags:

```html
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>
```

### JavaScript Functions & Events

Functions are blocks of code executed when called. They are often triggered by events, like button clicks.

### JavaScript in `<head>` or `<body>`

Scripts can go in the `<head>` or `<body>` section, or both.

#### JavaScript in `<head>`

Example of a script in the `<head>`:

```html
<head>
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</head>
```

#### JavaScript in `<body>`

Example of a script in the `<body>`:

```html
<body>
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</body>
```

Placing scripts at the bottom of `<body>` speeds up page display.

### External JavaScript

JavaScript can be placed in external `.js` files:

Example: `myScript.js`:

```javascript
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
```

To reference it in HTML:

```html
<script src="myScript.js"></script>
```

### External JavaScript Advantages

* Separates HTML from code
* Easier to maintain
* Faster page loads via caching

You can add multiple external scripts:

```html
<script src="myScript1.js"></script>
<script src="myScript2.js"></script>
```

### External References

* Full URL:

```html
<script src="https://www.example.com/myScript.js"></script>
```

* File path:

```html
<script src="/js/myScript.js"></script>
```

* No path:

```html
<script src="myScript.js"></script>
```
