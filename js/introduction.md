# Introduction

### What is JavaScript?

JavaScript is a web programming language that can modify HTML, CSS, and perform calculations.

### Why Study JavaScript?

It is essential for web developers alongside HTML and CSS to create interactive web pages.

### JavaScript Changes HTML Content

JavaScript can alter HTML content using methods like `getElementById()`:

```javascript
document.getElementById("demo").innerHTML = "Hello JavaScript";
```

### JavaScript Modifies HTML Attributes

JavaScript can update attributes, like the `src` of an image:

```html
<img id="lightbulb" src="off.png">
<button onclick="changeImage()">Turn on light</button>
```

### JavaScript Alters HTML Styles (CSS)

JavaScript can adjust element styles such as font size:

```javascript
document.getElementById("demo").style.fontSize = "35px";
```

### JavaScript Hides HTML Elements

Elements can be hidden by setting `display` to `none`:

```javascript
document.getElementById("demo").style.display = "none";
```

### JavaScript Shows HTML Elements

To show elements, change `display` to `block`:

```javascript
document.getElementById("demo").style.display = "block";
```
