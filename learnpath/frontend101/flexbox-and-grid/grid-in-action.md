# Grid in action

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/jV8B24rSN5o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

CSS Grid Layout, commonly known as Grid, is a powerful layout system that allows you to create two-dimensional grid-based layouts in CSS. It provides a flexible and intuitive way to arrange and align elements within a grid container.

To use CSS Grid, you need to define a grid container and specify its properties. Here are the key concepts and properties associated with CSS Grid:

1. Grid Container Properties:

   - `display: grid;`: Defines an element as a grid container.

   - `grid-template-columns`: Specifies the size and number of columns in the grid.

   - `grid-template-rows`: Specifies the size and number of rows in the grid.

   - `grid-template-areas`: Defines named grid areas, which can be referenced by grid items.

   - `grid-template`: A shorthand property that combines `grid-template-rows`, `grid-template-columns`, and `grid-template-areas`.

   - `grid-gap` or `gap`: Sets the spacing between grid cells (columns and rows).

   - `justify-items`: Aligns grid items along the inline (horizontal) axis within their grid cells.

   - `align-items`: Aligns grid items along the block (vertical) axis within their grid cells.

   - `justify-content`: Aligns the grid within the grid container along the inline axis.

   - `align-content`: Aligns the grid within the grid container along the block axis.

2. Grid Item Properties:

   - `grid-column-start` and `grid-column-end`: Specifies the start and end positions of a grid item along the horizontal axis.

   - `grid-row-start` and `grid-row-end`: Specifies the start and end positions of a grid item along the vertical axis.

   - `grid-column` and `grid-row`: A shorthand property that combines `grid-column-start`, `grid-column-end`, `grid-row-start`, and `grid-row-end`.

   - `grid-area`: Specifies the grid area that a grid item should occupy.

   - `justify-self`: Aligns a grid item along the inline (horizontal) axis within its grid cell.

   - `align-self`: Aligns a grid item along the block (vertical) axis within its grid cell.

These properties enable you to define the structure and layout of the grid container and position grid items within the grid cells. You can specify the size of columns and rows, create named grid areas, control the spacing between cells, and align items along both axes.

> **HTML**:

```html
<div class="grid-container">
  <div class="grid-item">Item 1</div>
  <div class="grid-item">Item 2</div>
  <div class="grid-item">Item 3</div>
  <div class="grid-item">Item 4</div>
  <div class="grid-item">Item 5</div>
  <div class="grid-item">Item 6</div>
</div>
```

> **CSS**:

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 10px;
}

.grid-item {
  background-color: #ddd;
  padding: 20px;
  text-align: center;
}
```

In the above code, we have a container element with the class `grid-container` that serves as the grid container. Inside the container, we have six items with the class "grid-item".

The CSS code defines the following properties:

- `display: grid;`: Sets the display of the container as a grid.
- `grid-template-columns: repeat(3, 1fr);`: Specifies that the grid should have three columns of equal width (1fr means one fraction of the available space).
- `grid-gap: 10px;`: Sets a gap of 10 pixels between grid cells.
- `.grid-item`: Styles the grid items with a background color, padding, and centers the text.

With this code, the items will be arranged in a 3-column grid with equal-width columns and a gap of 10 pixels between them. You can modify the number of columns, column widths, and gap size to suit your specific layout needs.

CSS Grid provides a powerful and flexible layout system that supports responsive design. It allows you to create complex and dynamic layouts with ease, accommodating various screen sizes and content structures.

It's important to note that CSS Grid is supported in modern browsers. However, as with any CSS feature, it's always a good practice to check the browser compatibility of specific properties and features before using them.

### Resource Recommendation

1. <a href="https://youtu.be/rg7Fvvl3taU" target="_blank">Learn CSS Grid the easy way</a>
2. <a href="https://youtu.be/EiNiSFIPIQE" target="_blank">Learn CSS Grid - A 13 Minute Deep Dive</a>
