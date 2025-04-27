# Static, Relative, Absolute, Fixed, Sticky

In this section, we'll dive deeper into the different types of positioning available in CSS.

---

## 1. Static Position (Default)

- Elements are positioned according to the normal flow of the page.
- Top, right, bottom, left properties **do not affect** static elements.

```css
position: static;
```

---

## 2. Relative Position

- Element moves **relative** to its normal position.
- Top, right, bottom, and left **affect** the position.

```css
position: relative;
top: 10px;
left: 20px;
```

---

## 3. Absolute Position

- Element is positioned **relative to its nearest positioned ancestor**.
- If no positioned ancestor exists, it uses the **document body**.

```css
position: absolute;
top: 150px;
left: 50px;
```

---

## 4. Fixed Position

- Element is positioned **relative to the viewport**.
- It **stays in place** even when the page is scrolled.

```css
position: fixed;
top: 10px;
right: 10px;
```

---

## 5. Sticky Position

- Element **toggles between relative and fixed** depending on scroll position.
- Useful for sticky headers or menus.

```css
position: sticky;
top: 0;
```

**Important:** The parent container must have enough height for `sticky` to work properly.

---

# Quick Summary Table

| Position Type | Behavior                                 |
| ------------- | ---------------------------------------- |
| Static        | Default, normal document flow            |
| Relative      | Shifted relative to itself               |
| Absolute      | Relative to positioned ancestor          |
| Fixed         | Relative to viewport                     |
| Sticky        | Relative initially, then fixed on scroll |

---

# Master these and you'll control layouts like a boss! 🎯👑

---
