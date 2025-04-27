# Complex Grid Layouts

In this section, we'll create a more **complex layout** using CSS Grid, combining multiple rows and columns to build a web page with a header, sidebar, main content area, and footer.

---

## Setting Up a Complex Grid Layout

We can create a more complex grid structure by defining both **rows** and **columns** with varying sizes. In this example, we define a layout with:

- A **header** that spans both columns at the top.
- A **sidebar** on the left side of the page.
- A **main content area** on the right side.
- A **footer** that spans both columns at the bottom.

### CSS Grid Code:

```css
.container {
  display: grid;
  grid-template-columns: 1fr 3fr;
  grid-template-rows: auto 1fr auto;
  gap: 20px;
}
```

- **`grid-template-columns: 1fr 3fr;`**: This creates **2 columns**, where the first column takes **1 fraction** of the available space and the second column takes **3 fractions**.
- **`grid-template-rows: auto 1fr auto;`**: This creates **3 rows**:
  - The first and third rows (header and footer) adjust their height based on content (`auto`).
  - The second row (main content and sidebar) takes the remaining available space (`1fr`).

---

## Placing Items on the Grid

Now we position each element inside the grid:

- **Header** spans across both columns with `grid-column: 1 / 3`.
- **Sidebar** and **Main Content** are placed in the second row.
- **Footer** spans across both columns at the bottom.

### CSS for Items:

```css
.header {
  grid-column: 1 / 3;
}

.sidebar {
  grid-row: 2;
}

.main-content {
  grid-row: 2;
}

.footer {
  grid-column: 1 / 3;
}
```

---

## Final Layout

This layout structure divides the page into:

- **Header**: Spans the top row and both columns.
- **Sidebar**: Positioned in the first column of the second row.
- **Main Content**: Positioned in the second column of the second row.
- **Footer**: Spans the bottom row and both columns.

---

# With this complex layout, you've learned how to combine multiple rows and columns to create more intricate web designs. Next, we'll explore **Responsive Design with Grid Layout**.

---
