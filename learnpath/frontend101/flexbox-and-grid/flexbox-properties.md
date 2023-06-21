# Flexbox properties

Flexbox consists of various properties that control the behavior and positioning of flex items. Here's an explanation of the main Flexbox properties:

1. **Container Properties**:

   - `display: flex;`: Defines an element as a flex container, establishing a flex formatting context.

   - `flex-direction`: Specifies the direction of the flex container's main axis. It can be set to `row` (horizontal), `row-reverse`, `column` (vertical), or `column-reverse`.

   - `flex-wrap`: Determines whether flex items should wrap to multiple lines if they exceed the container's width. It can be set to `nowrap` (default), `wrap`, or `wrap-reverse`.

   - `justify-content`: Aligns flex items along the main axis of the flex container. It can be set to `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, or `space-evenly`.

   - `align-items`: Aligns flex items along the cross axis of the flex container. It can be set to `flex-start`, `flex-end`, `center`, `baseline`, or `stretch` (default).

   - `align-content`: Defines how multiple lines of flex items are aligned along the cross axis. It works similar to `justify-content` but applies to multiple lines. It can be set to `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, or `stretch`.

2. **Item Properties**:

   - `flex-grow`: Specifies how flex items grow to fill available space along the main axis. It determines the proportion of the available space each item should take up. It can be set to a positive number.

   - `flex-shrink`: Specifies how flex items shrink if the container is too small along the main axis. It determines the proportion of the negative space each item should take up. It can be set to a positive number.

   - `flex-basis`: Defines the initial size of flex items along the main axis before free space is distributed. It can be set to a length value (e.g., pixels) or `auto` (default).

   - `flex`: A shorthand property that combines `flex-grow`, `flex-shrink`, and `flex-basis` in that order.

   - `align-self`: Overrides the `align-items` value for individual flex items. It aligns a specific item along the cross axis. It can be set to `auto` (default), `flex-start`, `flex-end`, `center`, `baseline`, or `stretch`.

   - `order`: Specifies the order in which flex items appear. It can be set to a positive or negative integer value.

These properties allow you to control the layout and behavior of flex containers and their child flex items. You can control the direction, wrapping, alignment, and size distribution of items within the flex container.

By using a combination of these properties, you can create versatile and responsive layouts with ease. Flexbox is particularly useful for building dynamic and flexible UI components, such as navigation bars, card layouts, and flexible grids.
