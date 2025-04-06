# CSS Selectors

---

## What are CSS Selectors?

- CSS selectors are used to **select HTML elements** that you want to style.

---

## Types of CSS Selectors

We can divide CSS selectors into **5 main types**:

---

### Simple Selectors
- Select elements by tag, class, or id.
```css
h1 { color: red; }         /* tag selector */
.myClass { color: blue; }  /* class selector */
#myId { color: green; }    /* id selector */
```

---

### Combinator Selectors
- Select elements based on a **relationship** (like parent > child).
```css
div p { color: purple; }     /* descendant */
div > p { color: orange; }   /* direct child */
```

---

### Pseudo-class Selectors
- Select elements based on a **state or condition**.
```css
a:hover { color: red; }    /* when mouse is over */
li:first-child { color: blue; }
```

---

### Pseudo-element Selectors
- Select and style **part of an element**.
```css
p::first-line { font-weight: bold; }
p::before { content: "👉 "; }
```

---

### Attribute Selectors
- Select elements using **HTML attributes**.
```css
input[type="text"] {
  background-color: yellow;
}
```

---

## 📝 Summary

| Selector Type      | Example            | Use For                            |
|--------------------|--------------------|-------------------------------------|
| Simple             | `.class`, `#id`    | Tag, class, or id selection         |
| Combinator         | `div > p`          | Based on parent/child relationship |
| Pseudo-class       | `a:hover`          | Styling element states             |
| Pseudo-element     | `p::first-line`    | Styling part of an element         |
| Attribute          | `[type="text"]`    | Based on attributes                |

---

📚 CSS selectors give you **full control** over how you style your web pages.
```

