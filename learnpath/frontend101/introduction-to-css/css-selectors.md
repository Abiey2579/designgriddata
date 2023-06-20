# CSS Selectors

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/Z07d9Vu7GKM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

CSS selectors are powerful tools that allow you to target and style specific elements on a web page. They define the pattern or criteria for selecting elements that you want to apply styles to. Let's explore some commonly used CSS selectors:

### **1. Element Selector**:

The element selector targets elements based on their HTML tag names. It selects all instances of the specified element. Here's an example:

```css
p {
  color: blue;
}
```

In the above code, the `p` selector targets all `<p>` elements on the page and applies a blue color to their text.

### **2. Class Selector**:

The class selector targets elements based on their `class` attribute. It is denoted by a dot (.) followed by the class name. Here's an example:

```css
.my-class {
  background-color: yellow;
}
```

In the above code, the `.my-class` selector targets all elements with the `class` attribute set to "my-class" and applies a yellow background color to them. To use this selector, you would need to add `class="my-class"` to the HTML elements you want to select.

### **3. ID Selector**:

The ID selector targets elements based on their unique `id` attribute. It is denoted by a hash (#) followed by the ID name. Here's an example:

```css
#my-id {
  font-weight: bold;
}
```

In the above code, the `#my-id` selector targets the element with the `id` attribute set to "my-id" and applies a bold font weight to it. To use this selector, you would need to add `id="my-id"` to the HTML element you want to select. Remember, IDs must be unique within the HTML document.

### **4. Attribute Selector**:

The attribute selector targets elements based on their attribute values. It allows you to select elements that have a specific attribute, regardless of the attribute's value. Here's an example:

```css
input[type="text"] {
  border: 1px solid gray;
}
```

In the above code, the `input[type="text"]` selector targets all `<input>` elements with the `type` attribute set to "text" and applies a gray border to them.

### **5. Descendant Selector**:

The descendant selector targets elements that are descendants of a specific parent element. It selects elements that are nested inside another element. Here's an example:

```css
ul li {
  color: red;
}
```

In the above code, the `ul li` selector targets all `<li>` elements that are descendants of a `<ul>` element and applies a red color to their text.

These are just a few examples of CSS selectors. There are many more selectors available, such as the descendant selector (`>`) for direct children, the pseudo-class selector (`:hover`, `:nth-child()`, etc.) for specific states or positions, and more. CSS selectors provide a powerful way to target and style specific elements in your web pages.

### Resource Recommendation

1. <a href="https://youtu.be/l1mER1bV0N0" target="_blank">Learn Every CSS Selector In 20 Minutes</a>
