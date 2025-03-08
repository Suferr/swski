# Output

### JavaScript Display Methods

JavaScript can display data in multiple ways:

* `innerHTML` or `innerText` to modify HTML content or text.
* `document.write()` for output.
* `window.alert()` for an alert box.
* `console.log()` for logging data.

### Using `innerHTML`

Example of displaying content in an HTML element:

```html
<p id="demo"></p>
<script>
document.getElementById("demo").innerHTML = "<h2>Hello World</h2>";
</script>
```

### Using `innerText`

Example of displaying text in an HTML element:

```html
<p id="demo"></p>
<script>
document.getElementById("demo").innerText = "Hello World";
</script>
```

### Using `document.write()`

For testing purposes, `document.write()` can output directly to the document:

```html
<script>
document.write(5 + 6);
</script>
```

Note: It erases the document content if used after the page loads.

### Using `window.alert()`

To display a message in an alert box:

```html
<script>
alert(5 + 6);
</script>
```

### Using `console.log()`

For debugging purposes, display output in the console:

```html
<script>
console.log(5 + 6);
</script>
```

### JavaScript Print

To print the current page content, use `window.print()`:

```html
<button onclick="window.print()">Print this page</button>
```

### Exercise: Incorrect Syntax

Which is not valid for writing output in JavaScript?

* `window.alert()`
* `console.log()`
* `body.html()` (Incorrect)
* `document.write()`
