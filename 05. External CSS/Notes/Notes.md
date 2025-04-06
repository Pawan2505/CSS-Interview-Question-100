
# 🌐 External CSS
---

## What is External CSS?

- CSS is written in a **separate file** (example: `style.css`)
- Linked to HTML using the `<link>` tag
- Used to style **many HTML pages** with one CSS file

---

## 📄 HTML File (index.html)

```html
<!DOCTYPE html>
<html>
<head>
  <title>External CSS</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Hello World</h1>
  <p>This is styled using External CSS</p>
</body>
</html>
```

---

## 🎨 CSS File (style.css)

```css
body {
  background-color: lightgray;
}

h1 {
  color: blue;
}

p {
  font-size: 18px;
  color: black;
}
```

---

## 📝 Output

- Background: light gray  
- Heading: blue  
- Paragraph: black text, bigger size

---

## 👍 Good For:

- Large websites  
- Reusing styles  
- Clean and organized code
```
