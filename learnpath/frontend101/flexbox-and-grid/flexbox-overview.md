# Flexbox Overview

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/u044iM9xsWU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

Flexbox, also known as Flexible Box Layout, is a powerful CSS layout module that provides a flexible way to arrange and align elements within a container. It allows you to create dynamic and responsive layouts, making it easier to build complex web designs.

To use Flexbox, you need to apply the following properties to the parent container (also known as the flex container) and the child elements (also known as flex items):

1. Flex Container Properties:

   - `display: flex;` or `display: inline-flex;`: Defines the container as a flex container. This property is applied to the parent element.

   - `flex-direction: row | row-reverse | column | column-reverse;`: Determines the direction of the main axis along which flex items are placed. The main axis can be horizontal (row) or vertical (column).

   - `flex-wrap: nowrap | wrap | wrap-reverse;`: Specifies whether flex items should wrap onto multiple lines if there is not enough space on a single line.

   - `justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;`: Aligns flex items along the main axis, distributing space between or around the items.

   - `align-items: flex-start | flex-end | center | baseline | stretch;`: Aligns flex items along the cross axis, perpendicular to the main axis.

   - `align-content: flex-start | flex-end | center | space-between | space-around | stretch;`: Defines how multiple lines of flex items are aligned along the cross axis when there is extra space in the container.

2. Flex Item Properties:

   - `order: <integer>;`: Specifies the order in which flex items appear. By default, flex items have an order of 0.

   - `flex-grow: <number>;`: Determines how flex items grow to fill available space along the main axis. A higher value means the item will grow proportionally more.

   - `flex-shrink: <number>;`: Controls how flex items shrink when there is not enough space along the main axis. A higher value means the item will shrink proportionally more.

   - `flex-basis: <length> | auto;`: Specifies the initial size of a flex item along the main axis before free space is distributed.

   - `flex: <flex-grow> <flex-shrink> <flex-basis>;`: A shorthand property that combines `flex-grow`, `flex-shrink`, and `flex-basis` into a single declaration.

   - `align-self: auto | flex-start | flex-end | center | baseline | stretch;`: Overrides the alignment specified by `align-items` for a specific flex item.

Flexbox provides a powerful and intuitive way to create flexible and responsive layouts. It simplifies the process of positioning and aligning elements, eliminating the need for complex float and positioning techniques.

It's important to note that Flexbox is well-supported in modern browsers, but it's always a good practice to check the browser compatibility of specific Flexbox properties and features before using them.

### Resource Recommendation

1. <a href="https://youtu.be/phWxA89Dy94" target="_blank">Learn Flexbox CSS in 8 minutes</a>
