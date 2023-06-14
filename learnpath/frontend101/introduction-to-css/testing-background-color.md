# Testing Background Color

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/kHUv8RAXsW4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

To add a background color using HTML and CSS. Here's a step-by-step guide:

Step 1: Create an HTML file. You can do this by `CTRL + N` then save it with a .html extension. For example, you can name it `index.html`.

Step 2: Set up the HTML structure copy and paste this basic HTML structure into your file:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Background Color Example</title>
  </head>
  <body></body>
</html>
```

Step 3: Create a CSS file. Similar to the way you created your `index.html` except this time your are using `.css` extension. For example, you can name your css file like `styles.css`. This is where we will define the background color.

Step 4: Link the CSS file to HTML
In the HTML file, between the `<head>` tags, add a `<link>` tag to link the CSS file:

```html
<link rel="stylesheet" type="text/css" href="styles.css" />
```

> **Note**: Keep your css file and html file together, else it won't work

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Background Color Example</title>
    <link rel="stylesheet" type="text/css" href="styles.css" />
  </head>
  <body></body>
</html>
```

Make sure the `href` attribute points to the correct location of your CSS file.

Step 5: Define the background color in CSS
Open the CSS file (styles.css) and add the following CSS rule:

```css
body {
  background-color: #f2f2f2;
}
```

In this example, we're setting the background color to a light gray `#f2f2f2`, but you can replace it with any valid color value you desire like `white` or `red` or `black` it will all work.

Step 6: Save the files and test, save both the HTML and CSS files. Open the HTML file in a web browser by right-clicking anywhere in your code and select `open in browser` _`(This will only work for sublime)`_ , and you should see the background color applied to the entire page.

Congratulations! You have successfully added a background color using HTML and CSS. Feel free to experiment with different colors.

### Resource Recommendation

1. <a href="https://youtu.be/s4mVpceYS7Y" target="_blank">How to Change Background Color with CSS</a>
2. <a href="https://youtu.be/5Vwa4KUZHq4" target="_blank">Changing background color - html css tutorial</a>
