## CSS Grid: `fr` Unit

The `fr` unit in CSS Grid stands for "fraction". It is used to define a portion of the available space in the grid container. For example, `1fr` represents one fraction of the available space, and `2fr` represents two fractions of the available space. This unit is useful for creating flexible and responsive grid layouts.

### Examples

```css
.grid-container {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  grid-template-rows: 1fr 2fr 1fr;
}
```