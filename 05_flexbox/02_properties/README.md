# Flexbox Properties

In this section, we’ll explore the key **Flexbox properties** that control the layout and alignment of elements inside a flex container.

---

## Key Flexbox Properties:

1. **display: flex**

   - This property is used to activate Flexbox on a container.
   - When `display: flex` is applied, the container becomes a flex container, and its direct children become flex items.

2. **justify-content**
   - Controls the alignment of items **along the main axis** (by default, this is the horizontal axis).
   - Common values:
     - `flex-start`: Aligns items to the start.
     - `flex-end`: Aligns items to the end.
     - `center`: Centers items.
     - `space-between`: Distributes items with equal space between them.
     - `space-around`: Distributes items with equal space around them.

```css
.container {
  justify-content: space-between;
}
```

3. **align-items**
   - Controls the alignment of items **along the cross axis** (perpendicular to the main axis, which is usually vertical).
   - Common values:
     - `stretch`: Stretch items to fill the container (default).
     - `flex-start`: Aligns items to the top.
     - `flex-end`: Aligns items to the bottom.
     - `center`: Centers items.

```css
.container {
  align-items: center;
}
```

4. **flex-direction**
   - Determines the direction in which the flex items are placed in the flex container.
   - Values:
     - `row`: Default. Items are placed horizontally.
     - `column`: Items are placed vertically.
     - `row-reverse`: Items are placed horizontally in reverse.
     - `column-reverse`: Items are placed vertically in reverse.

```css
.container {
  flex-direction: column;
}
```

---

## Example:

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-direction: row;
}
```

This layout will align the items horizontally, spread them out, and center them vertically.

---

# Experiment with different Flexbox properties to create unique layouts! 🎨

---
