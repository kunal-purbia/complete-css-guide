# Responsive Grid Layout

In this section, we'll explore how to make a grid layout **responsive**, meaning it will adapt to different screen sizes (such as mobile, tablet, or desktop) using **media queries**.

---

## What is a Responsive Grid Layout?

A **responsive grid layout** ensures that the web page content adjusts automatically according to the screen size. This is achieved by using **CSS Grid** along with **media queries** to modify the layout based on the viewport size.

### Basic Grid Layout:

The default layout has three equal-width columns:

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
```

This creates a 3-column grid where each column is equally sized.

---

## Media Queries for Responsiveness

We use **media queries** to change the grid layout for different screen sizes.

### For Tablets (max-width: 768px):

```css
@media (max-width: 768px) {
  .container {
    grid-template-columns: repeat(2, 1fr);
  }
}
```

- The grid switches to **2 columns** when the screen width is **768px** or smaller.

### For Mobile Devices (max-width: 480px):

```css
@media (max-width: 480px) {
  .container {
    grid-template-columns: 1fr;
  }
}
```

- The grid switches to a **single column** layout when the screen width is **480px** or smaller.

---

## Final Layout

- **Desktop View**: Displays 3 columns.
- **Tablet View**: Displays 2 columns.
- **Mobile View**: Displays a single column.

---
