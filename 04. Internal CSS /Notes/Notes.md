# 🔸 Internal CSS

**Internal CSS** is used to add styles **within a single HTML page**.

We write internal CSS inside the `<style>` tag, which is placed in the `<head>` section of the HTML document.

It allows us to style multiple elements on the same page, but the styles will **not affect other pages**.

---

## ✅ Key Points:
- Written inside the `<style>` tag in the `<head>`.
- Useful when you want styles **only for one HTML page**.
- Better than inline CSS when styling **multiple elements**.

---

## 🧾 Syntax Example:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Internal CSS</title>
  <style>
    body {
      background-color: #f9f9f9;
      font-family: Arial, sans-serif;
    }
    h1 {
      color: darkgreen;
    }
    p {
      font-size: 18px;
      color: #333;
    }
  </style>
</head>
<body>

  <h1>This is a Heading</h1>
  <p>This paragraph is styled using Internal CSS.</p>

</body>
</html>
