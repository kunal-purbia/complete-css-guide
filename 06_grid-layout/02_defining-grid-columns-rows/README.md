# Defining Grid Columns & Rows

In this section, we'll explore how to define both **columns** and **rows** in a grid layout. By using properties like `grid-template-columns` and `grid-template-rows`, you can customize the size and number of rows and columns in your grid.

---

## Defining Columns

You can define columns in a grid using the `grid-template-columns` property. For example:

```css
.container {
  grid-template-columns: repeat(3, 1fr);
}
```

This creates a grid with **three equal-width columns**. You can also specify different column sizes, such as fixed widths or percentages.

---

## Defining Rows

To define rows in your grid, use the `grid-template-rows` property. For example:

```css
.container {
  grid-template-rows: auto;
}
```

This will allow rows to grow or shrink based on the content inside them. You can also use fixed sizes or fractions to define the row heights.

---

## Spanning Columns and Rows

You can make items span across multiple columns or rows by using `grid-column` and `grid-row`. In the example below, **Item 1** spans **2 columns**, and **Item 5** spans **2 rows**.

```css
.item1 {
  grid-column: span 2;
}

.item5 {
  grid-row: span 2;
}
```

---

## Example

In the example provided, we create a grid with **3 equal-width columns** and **auto rows**. **Item 1** spans 2 columns, and **Item 5** spans 2 rows, creating a unique layout.

```html
<div class="container">
  <div class="item item1">Item 1</div>
  <div class="item item2">Item 2</div>
  <div class="item item3">Item 3</div>
  <div class="item item4">Item 4</div>
  <div class="item item5">Item 5</div>
</div>
```

This creates a grid layout where items are positioned and span across the grid as defined.

---

# Now that we've defined columns and rows, let's move on to placing items on the grid in the next section!

---
