---
description: Don't worry if you see new tags you’ll learn them soon!
---

# HTML Basics

## HTML Document Structure

Every HTML document must start with `<!DOCTYPE html>`.\
The document begins with `<html>` and ends with `</html>`.\
Visible content is inside `<body>` and `</body>`

Example:

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

**`<!DOCTYPE>` Declaration**

Defines the document type and helps browsers display pages correctly.\
Must be at the top, before any HTML tags.\
Not case-sensitive.

**HTML5 Doctype:**

```html
<!DOCTYPE html>
```

#### **HTML Headings**

Headings range from `<h1>` (most important) to `<h6>` (least important).

**Example:**

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```

***

#### **HTML Paragraphs**

Defined with the `<p>` tag.

**Example:**

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

***

#### **HTML Links**

Links are created using the `<a>` tag with the `href` attribute.

**Example:**

```html
<a href="https://www.example.com">This is a link</a>
```

Attributes provide extra info about elements. More on them later!

***

#### **HTML Images**

Images use the `<img>` tag with `src`, `alt`, `width`, and `height` attributes.

**Example:**

```html
<img src="example.jpg" alt="example image" width="104" height="142">
```

