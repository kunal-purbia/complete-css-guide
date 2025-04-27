# Placing Items on the Grid

In this section, we'll explore how to explicitly place items on the grid using **grid lines** and the `grid-column` and `grid-row` properties.

---

## Placing Items Using Grid Lines

You can specify exactly where each item should be placed on the grid using `grid-column` and `grid-row`. These properties accept values in the form of **grid lines** (starting and ending lines).

For example:

```css
.item1 {
  grid-column: 1 / 3;
  grid-row: 1;
}
```

- **`grid-column: 1 / 3;`** means that **Item 1** will start at **grid line 1** and span until **grid line 3**, covering two columns.
- **`grid-row: 1;`** means that **Item 1** will be placed in **row 1**.

---

## Example Layout

In the example provided, we have placed 5 items in a grid with 3 columns. Each item is placed at a specific grid location using `grid-column` and `grid-row`.

```css
.item1 {
  grid-column: 1 / 3;
  grid-row: 1;
}

.item2 {
  grid-column: 3;
  grid-row: 1;
}

.item3 {
  grid-column: 1;
  grid-row: 2;
}

.item4 {
  grid-column: 2;
  grid-row: 2;
}

.item5 {
  grid-column: 3;
  grid-row: 2;
}
```

This code places:

- **Item 1** in the first two columns of the first row.
- **Item 2** in the third column of the first row.
- **Item 3** in the first column of the second row.
- **Item 4** in the second column of the second row.
- **Item 5** in the third column of the second row.

---

## Grid Lines and Span

- **Grid lines** are the lines that separate columns and rows. You can use these lines to place your items exactly where you want them on the grid.
- You can span across multiple columns or rows by specifying multiple grid lines.

---

# With this, you now know how to place items on the grid. In the next section, we'll explore more advanced grid layouts and techniques.


---
