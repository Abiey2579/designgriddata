# Links and Images

To create a link, you can use the `<a>` element with the `href` attribute specifying the URL you want to link to. Here's an example:

```html
<a href="https://www.example.com">Visit Example Website</a>
```

To insert an image, you can use the `<img>` element with the `src` attribute specifying the URL of the image file. Here's an example:

```html
<img src="path/to/image.jpg" alt="Description of the image" />
```

Remember to replace `"path/to/image.jpg"` with the actual path or URL of your image file, and provide a meaningful description in the `alt` attribute for accessibility purposes.

By using these elements, you can create clickable links and display images within your HTML documents.

### **Let's learn by doing**

---

**Let's Add Image**

Copy any image and paste it in the same folder as your `index.html`, in case you keep your `index.html` in desktop just paste the image in desktop too. (The Idea is to keep the `index.html` and the image in the same place)

I have an image called `links-and-images.png`

> **NOTE:** Avoid using space when naming the image use **Hyphens** `-` or **Underscores** `_` or no space at all

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <img src="links-and-images.png" />
  </body>
</html>
```

Then right-click anywhere in code and select "Open in Browser"

You will see something like:

![Code Preview](https://raw.githubusercontent.com/Abiey2579/designgriddata/master/learnpath/assets/images/links-and-images-code-preview.jpg)

**Let's Add Link**

Links in HTML are also called **Anchor Tags**

Now Let's create an anchor tag that visits google.com, as you already know the `href` attribute specifying the URL you want to link to. Here's an example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <img src="links-and-images.png" />
    <a href="https://google.com">Google</a>
  </body>
</html>
```

> Make sure to add `https://` or else it won't work

Then right-click anywhere in code and select "Open in Browser"

You will see something like:

![Code Preview](https://raw.githubusercontent.com/Abiey2579/designgriddata/master/learnpath/assets/images/links-and-images-code-preview-2.jpg)

To check whether the anchor tag works click on it.

This is what I have, what about you?

![Code Preview](https://raw.githubusercontent.com/Abiey2579/designgriddata/master/learnpath/assets/images/links-and-images-code-preview-3.jpg)

### Resource Recommendation

1. <a href="https://youtu.be/_w6N_nplmAw" target="_blank">15: How to Insert Images Using HTML and CSS | Learn HTML and CSS | Full Course For Beginners</a>
2. <a href="https://youtu.be/D6aHo1VvCc8" target="_blank">How To Use An Image As A Link In HTML</a>
3. <a href="https://youtu.be/u2BtHQwxq7E" target="_blank">Images | HTML | Tutorial 9</a>
