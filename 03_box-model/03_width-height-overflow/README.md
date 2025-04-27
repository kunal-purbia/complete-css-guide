# Width, Height, and Overflow

In this section, we explore how **width**, **height**, and **overflow** work within the CSS Box Model.

---

## Width and Height

- **Width** and **height** set the size of the content area inside an element.
- You can define them using `px`, `%`, `em`, `rem`, `vw`, `vh`, etc.

Example:
```css
width: 250px;
height: 100px;
```

---

## Overflow

When content is too big to fit in an element's box, the `overflow` property controls what happens.

**Common overflow values:**
- `visible` (default): Content spills outside the box.
- `hidden`: Overflow content is clipped (not visible).
- `scroll`: Always adds scrollbars.
- `auto`: Adds scrollbars only when needed.

Example:
```css
overflow: auto;
```

In our example, scrollbars will appear if the text exceeds the box height or width.

---

## Key Point:

Understanding **overflow** is essential for handling long content and maintaining clean layouts!

---

# Keep Growing! 📏📦✨
```

---