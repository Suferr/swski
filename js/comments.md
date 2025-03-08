# Comments

### Single-line Comments

A single-line comment starts with `//`. Everything after `//` until the end of the line will be ignored by JavaScript.

Example 1: Commenting before a line of code:

<pre class="language-javascript"><code class="lang-javascript"><strong>// Update the heading:
</strong>document.getElementById("myHeading").innerHTML = "Welcome!";

// Update the paragraph:
document.getElementById("myParagraph").innerHTML = "Hello World!";
</code></pre>

Example 2: Commenting at the end of the line:

```javascript
let x = 5;      // Assign 5 to variable x
let y = x + 2;  // Add 2 to x and assign it to y
```

### Multi-line Comments

A multi-line comment begins with `/*` and ends with `*/`. It allows you to comment out multiple lines of code.

Example:

```javascript
/*
This code changes the content
of the elements with IDs "myHeading" and "myParagraph".
*/
document.getElementById("myHeading").innerHTML = "Welcome!";
document.getElementById("myParagraph").innerHTML = "Hello World!";
```

Multi-line comments are typically used for more detailed documentation, but single-line comments are more commonly used.

### Disabling Code Using Comments

Comments can also be used to temporarily disable code lines for testing purposes.

Example 1: Commenting a single line to disable it:

```javascript
//document.getElementById("myHeading").innerHTML = "Welcome!";
document.getElementById("myParagraph").innerHTML = "Hello World!";
```

Example 2: Using a multi-line comment block to disable multiple lines:

```javascript
/*
document.getElementById("myHeading").innerHTML = "Welcome!";
document.getElementById("myParagraph").innerHTML = "Hello World!";
*/
```

\


O
