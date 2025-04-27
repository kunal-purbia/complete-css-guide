# CSS Position Property

The `position` property in CSS determines how an element is positioned in a document.

---

## Common Position Values:

| Value    | Behavior                                                       |
| -------- | -------------------------------------------------------------- |
| static   | Default positioning (normal flow).                             |
| relative | Positioned relative to its normal position.                    |
| absolute | Positioned relative to the nearest positioned ancestor.        |
| fixed    | Positioned relative to the viewport (screen).                  |
| sticky   | Acts like relative until it hits a defined point, then sticks. |

---

## Example:

```css
.box {
  position: relative;
  top: 10px;
  left: 20px;
}
```

- Here, the box moves **10px down** and **20px to the right** from its normal position.

---

## Important Notes:

- If no `positioned` ancestor exists for an `absolute` element, it will be positioned relative to the `<html>` (document).
- Sticky positioning requires specific conditions like `top`, `bottom`, etc., and sometimes a set `height` on the parent.

---

# Master Position, Master Layouts! 📐🚀

```

---
```
