---
description: >-
  Attributes add extra information to HTML elements. They are placed in the
  start tag and use the name="value" format.
---

# HTML Attributes

#### **Common HTML Attributes**

**1. `href` (Hyperlink Reference)**

Specifies the URL for a link.

```html
<a href="https://example.com">Visit Example</a>
```

**2. `src` (Image Source)**

Defines the location of an image.

```html
<img src="image.jpg">
```

* **Absolute URL**: Links to an external image.
* **Relative URL**: Links to an image on your website (preferred).

**3. `width` & `height` (Image Dimensions)**

Controls the size of an image in pixels.

```html
<img src="image.jpg" width="400" height="300">
```

**4. `alt` (Alternative Text)**

Displays text if the image doesn't load (useful for accessibility).

```html
<img src="missing.jpg" alt="A scenic view">
```

**5. `style` (Inline CSS)**

Adds custom styling directly to an element.

```html
<p style="color:blue;">This is a blue paragraph.</p>
```

**6. `lang` (Page Language)**

Declares the document's language for search engines and accessibility.

```html
<html lang="en">
```

You can also specify a country code:

```html
<html lang="fr-CA">
```

**7. `title` (Tooltip Text)**

Shows a tooltip when hovering over an element.

```html
<p title="Hover text appears here">Hover over this text.</p>
```
