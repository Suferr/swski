---
description: An HTML element consists of a start tag, content, and an end tag.
---

# HTML Elements



**Example:**

```html
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

* `<h1>` is the **start tag**, "My First Heading" is the **content**, and `</h1>` is the **end tag**.
* `<br>` is an **empty element** (no content or end tag).

***

#### **Nested HTML Elements**

Elements can be **nested** inside others.

**Example:**

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

* `<html>` is the **root element**, containing everything.
* `<body>` holds the visible content.
* `<h1>` and `<p>` are inside `<body>`.

***

#### **Never Skip End Tags**

Some browsers may still display elements without an end tag, but this can cause errors.

**Example (Incorrect, but may still work):**

```html
<p>This is a paragraph
<p>This is another paragraph
```

Always close your tags properly!

***

#### **Empty Elements**

Some elements, like `<br>`, have no content or closing tag.

**Example:**

```html
<p>This is a <br> paragraph with a line break.</p>
```

***

#### **HTML is Not Case Sensitive**

Tags `<P>` and `<p>` are the same, but **lowercase** is recommended.

**Quick Reference:**

| Tag              | Description          |
| ---------------- | -------------------- |
| `<html>`         | Root of the document |
| `<body>`         | Document body        |
| `<h1>` to `<h6>` | Headings             |
