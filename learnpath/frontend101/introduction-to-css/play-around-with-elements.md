# Play around with elements

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/3ncFpP8GP4g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

CSS pseudo-elements are a powerful feature that allows you to style specific parts of an HTML element without the need for additional markup. Pseudo-elements are denoted by double colons (::) and provide a way to create and style virtual elements in the document tree. Let's explore some commonly used CSS pseudo-elements and provide code samples for each:

### `::before`:

The ::before pseudo-element allows you to insert content before the content of an element. It is often used to add decorative elements or icons. Here's an example:

```css
.icon::before {
  content: "";
  display: inline-block;
  width: 20px;
  height: 20px;
  background-color: blue;
}
```

In the above code, the ::before pseudo-element is applied to elements with the class "icon." The `content` property specifies the content to be inserted, which in this case is an empty string. The `display`, `width`, and `height` properties are used to define the size and behavior of the pseudo-element, and the `background-color` property sets its background color to blue.

### `::after`:

The ::after pseudo-element is similar to ::before, but it inserts content after the content of an element. It can also be used for decorative purposes. Here's an example:

```css
.button::after {
  content: "→";
  margin-left: 5px;
}
```

In the above code, the ::after pseudo-element is applied to elements with the class "button." The `content` property specifies the content to be inserted, in this case, an arrow character ("→"). The `margin-left` property adds some spacing between the original content and the pseudo-element.

### `::first-line`:

The ::first-line pseudo-element allows you to style the first line of text within a block-level element. It is commonly used for adjusting the appearance of headings or paragraphs. Here's an example:

```css
h1::first-line {
  font-size: 24px;
  color: red;
}
```

In the above code, the ::first-line pseudo-element is applied to `<h1>` elements. The `font-size` property increases the font size of the first line to 24 pixels, and the `color` property sets its color to red.

### `::selection`:

The ::selection pseudo-element targets the portion of text that is selected by the user. It allows you to style the selected text with custom properties. Here's an example:

```css
::selection {
  background-color: yellow;
  color: black;
}
```

In the above code, the `::selection` pseudo-element is used to style the background color and text color of the selected text. In this case, the selected text will have a yellow background and black text color.

These are just a few examples of CSS pseudo-elements. There are more pseudo-elements available, such as `::before`, `::after`, `::placeholder`, and `::marker`, among others. Pseudo-elements provide a way to enhance the presentation of your HTML elements without adding extra markup to your HTML structure.

### Resource Recommendation

1. <a href="https://youtu.be/OtBpgtqrjyo" target="_blank">Learn CSS Pseudo Elements In 8 Minutes</a>
