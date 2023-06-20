# Inline, Internal and External CSS

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/bL-E2pm1o8A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

CSS (Cascading Style Sheets) is a language used for describing the presentation of a document written in HTML (Hypertext Markup Language). Inline, internal, and external CSS are three different ways of applying styles to HTML elements. Let's dive into each of them:

### **1. Inline CSS:**

Inline CSS is used to apply styles directly to individual HTML elements. This approach involves adding the `style` attribute to an HTML tag and specifying the CSS properties and values within it. Here's an example:

```html
<p style="color: blue; font-size: 18px;">
  This is a paragraph with inline CSS.
</p>
```

In the above code snippet, the `style` attribute is used to set the color to blue and font size to 18 pixels for the paragraph `<p>` element.

### **2. Internal CSS:**

Internal CSS is defined within the `<style>` tags in the `<head>` section of an HTML document. It allows you to apply styles to multiple elements within a single HTML file. Here's an example:

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      p {
        color: red;
        font-size: 20px;
      }

      .highlight {
        background-color: yellow;
      }
    </style>
  </head>
  <body>
    <p>This is a paragraph with internal CSS.</p>
    <p class="highlight">
      This paragraph has the "highlight" class applied to it.
    </p>
  </body>
</html>
```

In the above code snippet, the CSS styles are defined within the `<style>` tags. The `p` selector selects all `<p>` elements and applies the specified styles to them. The `.highlight` selector targets elements with the class "highlight" and sets their background color to yellow.

### **3. External CSS:**

External CSS is stored in a separate CSS file and linked to the HTML document using the `<link>` tag. This approach allows you to apply styles across multiple HTML files, promoting code reusability. Here's an example:

> **styles.css** (external CSS file):

```css
p {
  color: green;
  font-size: 24px;
}

.highlight {
  background-color: cyan;
}
```

> **index.html** (HTML file):

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <p>This is a paragraph with external CSS.</p>
    <p class="highlight">
      This paragraph has the "highlight" class applied to it.
    </p>
  </body>
</html>
```

In the above code snippet, the CSS styles are defined in the **styles.css** file. The `<link>` tag in the **index.html** file references the external CSS file using the `href` attribute, allowing the styles to be applied to the HTML elements.

These are the three main ways to apply CSS styles to HTML elements. Each method has its use cases, and the choice depends on the specific requirements of your project. Remember that inline CSS overrides internal and external CSS, and external CSS takes precedence over internal CSS due to the cascading nature of CSS.

### Resource Recommendation

1. <a href="https://youtu.be/6EMkq7UqMGE" target="_blank">INTRODUCTION TO CSS - CASCADING STYLE SHEETS (EXTERNAL, INTERNAL & INLINE CSS)</a>
