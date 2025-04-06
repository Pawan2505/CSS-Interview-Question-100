## 💬 What is `@keyframes` in CSS?

`@keyframes` is used to create **animations** in CSS.

It tells the browser:

➡️ **Where to start**  
➡️ **Where to end**  
➡️ **And how things should move or change in between**

---

### ✅ Example:

```css
@keyframes moveBox {
  from {
    left: 0;
  }
  to {
    left: 200px;
  }
}

.box {
  position: relative;
  width: 100px;
  height: 100px;
  background: red;
  animation: moveBox 2s linear infinite;
}
```

🧠 This makes the red box move to the right again and again.

---

### 💡 In Short:

- `@keyframes` = animate anything (move, fade, resize)
- Works with the `animation` property
- Used for smooth, step-by-step changes


