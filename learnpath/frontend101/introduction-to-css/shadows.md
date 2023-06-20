# Shadows

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/-JNRQ5HjNeI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

Shadows in CSS are a powerful feature that allows you to add depth and dimension to your elements, enhancing their visual appearance. CSS provides properties to control box shadows and text shadows. Let's explore both of them with code samples:

### **1. Box Shadows**:

Box shadows are applied to the entire box of an element, including its content, padding, and border. The `box-shadow` property is used to create box shadows. Here's an example:

```css
.element {
  box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
}
```

In the above code, the `.element` class has a box shadow applied to it. The `box-shadow` property takes four values:

- `horizontal offset`: Specifies the horizontal offset of the shadow.
- `vertical offset`: Specifies the vertical offset of the shadow.
- `blur radius`: Specifies the blur radius of the shadow.
- `color`: Specifies the color of the shadow.

You can adjust these values as per your requirements. Negative offset values can be used to position the shadow in the opposite direction. The blur radius determines the blurriness of the shadow, with higher values producing a more blurred effect. The color can be specified using color names, hexadecimal codes, RGB, or RGBA values.

Additionally, you can create multiple box shadows on a single element by separating them with commas. This allows you to create complex shadow effects. Here's an example:

```css
.element {
  box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3), -2px -2px 4px rgba(255, 255, 255, 0.3);
}
```

In this code, the `.element` class has two box shadows applied. The first shadow is offset by 2 pixels horizontally and vertically, with a blur radius of 4 pixels and a semi-transparent black color. The second shadow is offset by -2 pixels horizontally and vertically, with the same blur radius and a semi-transparent white color. This creates a "raised" effect on one side and a "sunken" effect on the other side.

### **2. Text Shadows**:

Text shadows are applied specifically to the text content of an element. They can be used to add emphasis, create visual effects, or improve readability. The `text-shadow` property is used to create text shadows. Here's an example:

```css
.element {
  text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
}
```

In the above code, the `.element` class has a text shadow applied to it. The `text-shadow` property works similar to `box-shadow` and accepts the same four values: horizontal offset, vertical offset, blur radius, and color. You can adjust these values to achieve the desired text shadow effect.

Multiple text shadows can also be applied to the same element using commas. This allows you to create layered or gradient effects. Here's an example:

```css
.element {
  text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5), 2px 2px 4px rgba(0, 0, 0, 0.3);
}
```

In this code, the `.element` class has two text shadows applied. The first shadow is lighter and offset by 1 pixel, while the second shadow is darker and offset by 2 pixels. This creates a layered effect on the text.

### Resource Recommendation

1. <a href="https://youtu.be/Yon4l3MUBGY" target="_blank">CSS box-shadows - how to make them look good</a>
