# Responsive Flexbox

In this section, we will explore how to create **responsive layouts** using Flexbox by combining Flexbox properties and **media queries**. We’ll ensure that our design adapts seamlessly across different screen sizes.

---

## Media Queries in Flexbox

Using media queries allows us to make adjustments for different screen widths and create a responsive design.

### Example:

```css
@media screen and (max-width: 768px) {
  .container {
    justify-content: center;
  }
  .item {
    flex: 1 1 100%;
  }
}
```

- This media query targets screens that are **768px or smaller** and adjusts the flex items to stack vertically with full width (`flex: 1 1 100%`).

### Example for Smaller Screens:

```css
@media screen and (max-width: 480px) {
  .item {
    flex: 1 1 100%;
    min-width: 100%;
  }
}
```

- This ensures the items take up the full width even on **small mobile screens**.

---

## Combining Flexbox and Media Queries

Flexbox and media queries together allow us to create responsive, adaptable layouts. You can define how items are displayed across various screen sizes, making your layout flexible and user-friendly.

---

### Example Responsive Layout:

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
}

.item {
  flex: 1;
  min-width: 250px;
}

@media screen and (max-width: 768px) {
  .container {
    justify-content: center;
  }
  .item {
    flex: 1 1 100%;
  }
}

@media screen and (max-width: 480px) {
  .item {
    flex: 1 1 100%;
    min-width: 100%;
  }
}
```

---

# Now, you have a responsive Flexbox layout that adjusts perfectly to different screen sizes! 📱💻

---
