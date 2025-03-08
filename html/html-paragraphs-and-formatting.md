---
description: A paragraph always starts on a new line, and usually a block of text.
---

# HTML Paragraphs and Formatting

**Paragraphs (`<p>`)**

* Defines a block of text.
* Starts on a new line by default.
* Browsers add space (margin) above and below paragraphs.

**Example:**

```html
<p>This is a paragraph.</p>  
<p>This is another paragraph.</p>  
```

***

**Whitespace in HTML**

* Extra spaces and new lines in code are ignored by browsers.
* The text will display in a single block.

**Example:**

```html
<p>
  This paragraph  
  has many spaces  
  and new lines,  
  but the browser  
  ignores them.
</p>
```

***

**Horizontal Lines (`<hr>`)**

* Creates a thematic break (horizontal line).
* Useful for separating sections.

**Example:**

```html
<h1>Title</h1>  
<p>Some content.</p>  
<hr>  
<h2>New Section</h2>  
<p>More content.</p>  
```

***

**Line Breaks (`<br>`)**

* Adds a new line without starting a new paragraph.

**Example:**

```html
<p>This is<br>a line break.</p>  
```

***

**Preformatted Text (`<pre>`)**

* Preserves spaces and line breaks.
* Displays text in a fixed-width font.

**Example:**

```html
<pre>
  Roses are red,
  Violets are blue,
  HTML is awesome,
  And so are you.
</pre>
```

Use `<p>` for paragraphs, `<hr>` for section breaks, `<br>` for line breaks, and `<pre>` for preformatted text!
