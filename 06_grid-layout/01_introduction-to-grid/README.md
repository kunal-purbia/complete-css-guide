# Introduction to CSS Grid

In this section, we will introduce **CSS Grid Layout** and its basic usage.

---

## What is CSS Grid?

- **CSS Grid** is a powerful layout system in CSS that allows you to create complex and flexible two-dimensional layouts.
- With Grid, you can control both rows and columns simultaneously, giving you fine-grained control over your layout.

---

## Setting Up Grid

To set up a grid layout, use the `display: grid;` property on a container.

```css
.container {
  display: grid;
}
```

---

## Defining Columns

You can define the number of columns in your grid using `grid-template-columns`. In this example, we're creating a grid with two equal columns.

```css
.container {
  grid-template-columns: repeat(2, 1fr);
}
```

- `1fr` means **1 fraction** of the available space. So, both columns will share the available space equally.

---

## Example

In the example provided, we created a simple 2-column grid, where each item takes up one grid cell:

```html
<div class="container">
  <div class="item">Item 1</div>
  <div class="item">Item 2</div>
  <div class="item">Item 3</div>
  <div class="item">Item 4</div>
</div>
```

This will result in a 2x2 grid layout.

---

# Ready to dive deeper into CSS Grid? Next, we will learn how to define rows and columns in more detail.

---
