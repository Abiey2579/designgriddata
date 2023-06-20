# Background Images

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/zHZRFwWQt2w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

Background images allow you to set an image as the background of an HTML element, enhancing the visual appearance of your web page. Let's explore how to use background images with code samples:

To set a background image, you can use the `background-image` property in CSS. Here's an example:

```css
.element {
  background-image: url("image.jpg");
}
```

In the above code, the `.element` class has a background image specified using the `url()` function. The URL inside the parentheses points to the location of the image file. You can provide a relative or absolute path to the image file.

Here are some additional properties you can use to control the behavior of background images:

1. `background-repeat`: Determines how the background image repeats both horizontally and vertically. The possible values are:
   - `repeat` (default): The image is repeated both horizontally and vertically.
   - `repeat-x`: The image is repeated only horizontally.
   - `repeat-y`: The image is repeated only vertically.
   - `no-repeat`: The image is not repeated.

Example:

```css
.element {
  background-image: url("image.jpg");
  background-repeat: no-repeat;
}
```

2. `background-size`: Specifies the size of the background image. You can set it to a specific width and height or use special values like `cover` or `contain`. The possible values are:
   - `auto` (default): The image is displayed at its original size.
   - `cover`: The image is resized to cover the entire background while maintaining its aspect ratio. This may result in cropping of the image.
   - `contain`: The image is resized to fit within the background without cropping, maintaining its aspect ratio.

Example:

```css
.element {
  background-image: url("image.jpg");
  background-size: cover;
}
```

3. `background-position`: Determines the starting position of the background image. You can specify it using keywords (e.g., `top`, `center`, `bottom`, `left`, `right`) or with pixel values. The default value is `left top`.

Example:

```css
.element {
  background-image: url("image.jpg");
  background-position: center;
}
```

4. `background-attachment`: Specifies whether the background image scrolls with the content or remains fixed in place. The possible values are:
   - `scroll` (default): The background image scrolls with the content.
   - `fixed`: The background image remains fixed in place, even when scrolling.

Example:

```css
.element {
  background-image: url("image.jpg");
  background-attachment: fixed;
}
```

You can combine these properties to achieve different effects and create visually appealing backgrounds for your elements. It's worth noting that you can apply background images to various HTML elements, such as `<div>`, `<body>`, or specific elements using their class or ID selectors.

Here's an example that combines multiple background properties:

```css
.element {
  background-image: url("image.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
```

In this code snippet, the `.element` class has a background image that doesn't repeat, covers the entire background area, is centered, and remains fixed in place.

### Resource Recommendation

1. <a href="https://youtu.be/2ZHfxG9uEjI" target="_blank">How to add background image in Html and Css</a>
