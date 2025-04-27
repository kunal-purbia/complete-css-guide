# Introduction to Flexbox

In this section, we’ll cover the **basic structure** and how to use **Flexbox** to create a simple layout.

---

## What is Flexbox?

- **Flexbox** is a one-dimensional layout system designed to align and distribute space among items inside a container.
- It makes it easier to design complex layouts without using floats or positioning.
- Flexbox operates on the main axis (horizontal by default) and the cross axis (vertical).

---

## Basic Structure

We start by creating a container that will hold the items. We then apply `display: flex` to the container to enable Flexbox on it. The child items inside the container will automatically follow Flexbox rules.

---

### Example: Basic Flexbox Layout

```css
.container {
  display: flex;
}

.item {
  flex: 1; /* The items will be equally distributed */
}
```

---

## Key Concepts:

1. **Container**:
   - Apply `display: flex` to make it a flex container.
2. **Items**:
   - Items inside the flex container are flex items and will follow the Flexbox layout model.

---

## Quick Tips:

- You can adjust how items are distributed using `justify-content` (controls main axis alignment).
- The `flex` property controls how the space is shared between items (like `flex: 1` for equal distribution).

---

# Now you're ready to start exploring the power of Flexbox! 💪

---
