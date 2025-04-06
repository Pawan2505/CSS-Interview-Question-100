# 🔹 CSS Simple Selectors

---

## What are Simple Selectors?

Simple selectors help us style HTML elements using their:
- **ID** (unique element)
- **Class** (reusable group)

---

## 1️⃣ ID Selector (`#`)

- Used for **one unique element**
- In CSS, start with `#` followed by the id name

🔸 Example:

```html
<h1 id="title">Hello</h1>
```

```css
#title {
  color: blue;
}
```

---

## 2️⃣ Class Selector (`.`)

- Used for **many elements**
- In CSS, start with `.` followed by the class name

🔸 Example:

```html
<p class="info">This is info</p>
<p class="info">Another info</p>
```

```css
.info {
  color: green;
}
```

---

## 💡 Tip:

| Selector | Symbol | Use for          |
|----------|--------|------------------|
| ID       | `#`    | One element only |
| Class    | `.`    | Multiple items   |

---

🟢 Use ID for special things  
🟢 Use Class when styling many similar things
