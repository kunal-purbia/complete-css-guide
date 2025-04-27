# Flexbox in Action

In this section, we’ll see **Flexbox in action** by creating a responsive layout that adapts to different screen sizes. We'll use the properties we’ve learned so far, such as `justify-content`, `align-items`, `flex-wrap`, and `flex` to create flexible layouts.

---

## Responsive Layout with Flexbox

We'll use `flex-wrap` to allow items to **wrap** onto the next line when there isn't enough space, creating a responsive design.

### Example:

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;  /* Allow items to wrap to the next line */
}
```

This layout will allow items to wrap when the available space is insufficient.

---

### Flex Items

- **flex: 1** makes each item take equal space in the container.
- **min-width: 200px** ensures that items won’t shrink below this width, which helps maintain a responsive layout.

---

## Flexbox with Wrapping

```css
.container {
  flex-wrap: wrap;
}
```

This property makes the items wrap when the container's width is not enough to fit all the items.

---

## Example Layout:

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 20px;
}

.item {
  flex: 1;
  min-width: 200px;
}
```

This creates a layout where the items will stretch and align properly even on smaller screens.

---

# Now you can build flexible, responsive layouts with Flexbox! 🌟

---
