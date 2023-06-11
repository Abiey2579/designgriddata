# Forms

Forms in HTML are used to collect user input, such as text, selections, checkboxes, and more. They are essential for interactive web pages and allow users to submit data to a server for processing. Let's dive into the details of creating forms in HTML.

To create a form, you use the `<form>` element. Here's a basic form structure:

```html
<form action="/submit" method="POST">
  <!-- form elements go here -->
</form>
```

The `action` attribute specifies where the form data should be sent when submitted, and the `method` attribute specifies the HTTP method to be used (e.g., GET or POST).

Within the `<form>` element, you can add various form elements, such as text fields, checkboxes, radio buttons, dropdown menus, and more. Here are a few examples:

1. Text Input:

```html
<label for="name">Name:</label>
<input type="text" id="name" name="name" placeholder="Enter your name" />
```

2. Checkbox:

```html
<label for="checkbox"> Check me! </label>
<input type="checkbox" id="checkbox" name="checkbox" />
```

3. Dropdown Menu:

```html
<label for="color">Favorite Color:</label>
<select id="color" name="color">
  <option value="red">Red</option>
  <option value="blue">Blue</option>
  <option value="green">Green</option>
</select>
```

4. Radio:

```html
<label for="radio"> Click Me </label>
<input type="radio" id="radio" name="radio" />
```

5. Date:

```html
<label for="date"> Date of birth</label>
<input type="date" id="date" name="date" />
```

6. Textarea:

```html
<label for="radio"> Enter your mession </label>
<textarea row="10" col="10" id="textarea" name="textarea"></textarea>
```

7. File:

```html
<label for="file"> Choose file </label>
<input type="file" id="file" name="file" />
```

Once the form is filled out, users can submit the data. This is typically done using a submit button:

```html
<button type="submit">Submit</button>
```

### **Let's test them**

---

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <form action="/submit" method="POST">
      <label for="name">Name:</label> <br />
      <input type="text" id="name" name="name" placeholder="Enter your name" />
      <br /><br />
      <label for="checkbox"> Check me! </label> <br />
      <input type="checkbox" id="checkbox" name="checkbox" /> <br /><br />
      <label for="date"> Date of birth</label> <br />
      <input type="date" id="date" name="date" /> <br /><br />
      <label for="color">Favorite Color:</label><br />
      <select id="color" name="color">
        <br /><br />
        <option value="red">Red</option>
        <option value="blue">Blue</option>
        <option value="green">Green</option>
      </select>
      <label for="radio"> Click Me </label> <br />
      <input type="radio" id="radio" name="radio" /> <br /><br />
      <label for="radio"> Enter your mession </label> <br />
      <textarea row="10" col="10" id="textarea" name="textarea"></textarea>
      <br /><br />
      <label for="file"> Choose file </label> <br />
      <input type="file" id="file" name="file" /> <br /><br />
      <button type="submit">Submit</button>
    </form>
  </body>
</html>
```

You might notice something here `<br />`, this mean **Break line**, it typically takes the element right after it, and break it to next line, adding it twice make it **Breaks two line**.

Let's preview it

![Code Preview](https://raw.githubusercontent.com/Abiey2579/designgriddata/master/learnpath/assets/images/forms-code-preview.jpg)

### Resource Recommendation

1. <a href="https://youtu.be/fNcJuPIZ2WE" target="_blank">Learn HTML Forms In 25 Minutes</a>
