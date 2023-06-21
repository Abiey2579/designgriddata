# Main and Cross Axis

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/8vcSr1yVvXQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

In CSS, when working with flexbox layouts, it's essential to understand the concepts of the main axis and cross axis. These terms refer to the two primary axes along which flex items are aligned within a flex container.

1. **Main Axis**:

   - The main axis is the primary axis along which flex items are laid out. It can be either horizontal or vertical, depending on the `flex-direction` property applied to the flex container.
   - By default, the main axis runs from left to right (`flex-direction: row`) or from top to bottom (`flex-direction: column`).
   - The main axis is influenced by properties such as `justify-content` and `align-content`, which control the alignment and distribution of flex items along this axis.
   - For example, when `flex-direction: row` is set, the main axis is horizontal, and flex items are positioned from left to right. When `flex-direction: column` is set, the main axis is vertical, and flex items are positioned from top to bottom.

2. **Cross Axis**:
   - The cross axis is perpendicular to the main axis and is the secondary axis along which flex items are aligned.
   - It is vertical when the main axis is horizontal (`flex-direction: row`) and horizontal when the main axis is vertical (`flex-direction: column`).
   - The cross axis is influenced by properties such as `align-items` and `align-content`, which control the alignment and distribution of flex items along this axis.
   - For example, when `flex-direction: row` is set, the cross axis is vertical, and the alignment of flex items is controlled by `align-items` property. When `flex-direction: column` is set, the cross axis is horizontal, and the alignment is controlled by `justify-content`.

Understanding the main axis and cross axis is crucial for controlling the layout and alignment of flex items within a flex container. It allows you to position items in the desired direction and achieve the desired visual effect.

Remember that the main axis and cross axis can be influenced by the `flex-direction` property. By changing the value of `flex-direction`, you can switch the main axis from horizontal to vertical or vice versa.

It's also worth noting that the main axis and cross axis have different default behaviors for how flex items are aligned. By using the appropriate properties such as `justify-content`, `align-items`, `align-self`, and `align-content`, you can customize the alignment of flex items along both axes to create flexible and responsive layouts.

### Resource Recommendation

1. <a href="https://youtu.be/8EG8kbH0P88" target="_blank">Understand CSS Flexbox Layout Mechanism - Main Axis and Cross Axis</a>
