# Aligning Items in Flexbox

In this section, we will learn how to align items both **horizontally** and **vertically** within a flex container.

---

## Aligning Items Along the Cross-Axis

Flexbox allows you to align items **vertically** (perpendicular to the main axis) using the `align-items` property.

### **align-items: center**

This property aligns items **vertically at the center** of the container.

```css
.container {
  align-items: center;
}
```

### **align-items: flex-start**

This aligns items at the **top** of the container (start of the cross axis).

```css
.container {
  align-items: flex-start;
}
```

### **align-items: flex-end**

This aligns items at the **bottom** of the container (end of the cross axis).

```css
.container {
  align-items: flex-end;
}
```

### **align-items: stretch** (default)

By default, Flexbox stretches the items to **fill the container's height**.

```css
.container {
  align-items: stretch;
}
```

---

## Aligning Items Along the Main Axis

We can also align items **horizontally** using the `justify-content` property.

### **justify-content: center**

This centers items **horizontally**.

```css
.container {
  justify-content: center;
}
```

### **justify-content: space-between**

This distributes items with **equal space** between them.

```css
.container {
  justify-content: space-between;
}
```

### **justify-content: space-around**

This distributes items with **equal space** around them.

```css
.container {
  justify-content: space-around;
}
```

---

## Example:

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 300px;
}
```

This layout will center the items **both horizontally and vertically** in the container.

---

# Experiment with different alignments and explore the flexibility of Flexbox! 🎯

---
