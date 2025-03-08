---
description: A CSS rule consists of a selector and a declaration block.
---

# CSS Syntax

### **Structure of a CSS Rule**

A CSS rule consists of two main parts:

1. **Selector** – Targets the HTML element(s) to style.
2. **Declaration Block** – Contains styling rules inside `{}`.

Each declaration inside the block consists of:

* **Property** – The style attribute (e.g., `color`).
* **Value** – The setting for the property (e.g., `red`).
* Declarations are separated by semicolons (`;`).

***

### **Example**

The following CSS rule styles all `<p>` elements:

```css
tp {
  color: red;
  text-align: center;
}
```

#### **Explanation**

* `p` → **Selector** (applies styles to `<p>` elements).
* `color: red;` → Sets text color to red.
* `text-align: center;` → Centers the text.

This ensures that all paragraphs appear **red and centered.**
