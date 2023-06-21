# Grid properties

CSS Grid is a powerful layout module that allows you to create grid-based layouts with ease. Here's an explanation of the main properties used in CSS Grid:

1. **Container Properties**:

   - `display: grid;`: Specifies that an element should be treated as a grid container.

   - `grid-template-rows`: Defines the height of each row in the grid. You can specify the height using length values (e.g., pixels) or percentages.

   - `grid-template-columns`: Defines the width of each column in the grid. You can specify the width using length values or percentages. You can also use keywords like `auto` (automatic size based on content), `min-content` (minimum size based on content), or `max-content` (maximum size based on content).

   - `grid-template-areas`: Specifies named grid areas and their placement within the grid. You can use this property to create complex grid layouts by assigning areas to specific grid cells.

   - `grid-template`: A shorthand property that combines `grid-template-rows`, `grid-template-columns`, and `grid-template-areas` in that order.

   - `grid-gap`: Sets the size of the gap between rows and columns in the grid. It can be specified using length values.

   - `justify-items`: Aligns grid items along the horizontal axis within their respective grid cells. It can be set to `start`, `end`, `center`, `stretch`, or `baseline`.

   - `align-items`: Aligns grid items along the vertical axis within their respective grid cells. It can be set to `start`, `end`, `center`, `stretch`, or `baseline`.

   - `justify-content`: Aligns the grid within the grid container along the horizontal axis. It can be set to `start`, `end`, `center`, `stretch`, `space-between`, `space-around`, or `space-evenly`.

   - `align-content`: Aligns the grid within the grid container along the vertical axis. It can be set to `start`, `end`, `center`, `stretch`, `space-between`, `space-around`, or `space-evenly`.

2. **Item Properties**:

   - `grid-row-start`: Specifies the grid row on which an item starts.

   - `grid-row-end`: Specifies the grid row on which an item ends.

   - `grid-column-start`: Specifies the grid column on which an item starts.

   - `grid-column-end`: Specifies the grid column on which an item ends.

   - `grid-row`: A shorthand property that combines `grid-row-start` and `grid-row-end` in that order.

   - `grid-column`: A shorthand property that combines `grid-column-start` and `grid-column-end` in that order.

   - `grid-area`: A shorthand property that combines `grid-row-start`, `grid-column-start`, `grid-row-end`, and `grid-column-end` in that order.

   - `justify-self`: Aligns a grid item along the horizontal axis within its grid cell. It can be set to `start`, `end`, `center`, `stretch`, or `baseline`.

   - `align-self`: Aligns a grid item along the vertical axis within its grid cell. It can be set to `start`, `end`, `center`, `stretch`, or `baseline`.

These properties allow you to define the structure and placement of grid items within a grid container. You can control the size, positioning, and alignment of items using these properties.

By using a combination of container and item properties, you can create complex and responsive grid layouts that adapt to different screen sizes and content requirements.
