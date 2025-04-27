# Box Sizing

The `box-sizing` property controls how the total width and height of an element are calculated.

---

## 1. Content-Box (Default)

- Only the **content** area is controlled by `width` and `height`.
- Padding and border are **added** to the final size.
- This can make elements larger than expected.

Example:

```css
box-sizing: content-box;
```

---

## 2. Border-Box

- The **total size** (width + height) includes content, padding, and border.
- Padding and border **stay inside** the specified width and height.
- This method makes sizing easier and is widely preferred.

Example:

```css
box-sizing: border-box;
```

---

## Quick Visual:

| Property    | Behavior                                          |
| ----------- | ------------------------------------------------- |
| Content-Box | Width = content only; padding + border expand it  |
| Border-Box  | Width = content + padding + border (all included) |

---

## Why `border-box` is preferred:

✅ Easier to maintain consistent layouts.  
✅ No need to manually adjust widths when adding padding or borders.

You can even apply `border-box` universally:

```css
* {
  box-sizing: border-box;
}
```

---

# You're Now a Box Model Master! 📦👑

---
