# z-index and Overlapping Elements

When elements are positioned to overlap, the `z-index` property helps control which one appears on top!

---

## What is z-index?

- `z-index` defines the stack order of elements.
- An element with a **higher z-index** will be displayed in front of an element with a **lower z-index**.
- Only elements with a **position value** (relative, absolute, fixed, sticky) can use `z-index`.

---

## Example:

```css
.box {
  position: absolute;
  z-index: 1; /* lower priority */
}

.box2 {
  z-index: 2; /* will be above .box */
}

.box3 {
  z-index: 3; /* will be on top */
}
```

---

## Quick Tips:

- Default `z-index` is `auto`, meaning the browser follows the order in HTML.
- `z-index` only works on elements that have `position` set (not `static`).
- Negative `z-index` values are allowed (element moves behind others).

```css
.box {
  z-index: -1;
}
```

---

# Stacking Elements = Designing like a pro! 🎨🚀

---
