# How many types of CSS?

There are **3 types of CSS**:

1. **Inline CSS**  
   - CSS is written **inside the HTML tag** using the `style` attribute.
   - Used for small and quick changes.
   - Example: `<h1 style="color: red;">Hello</h1>`

2. **Internal CSS**  
   - CSS is written **inside the `<style>` tag** in the HTML file's `<head>` section.
   - Useful when styling a **single page**.
   - Example:
     ```html
     <style>
       h1 { color: blue; }
     </style>
     ```

3. **External CSS**  
   - CSS is written in a **separate file** with `.css` extension.
   - Linked using the `<link>` tag in HTML.
   - Best for styling **multiple pages**.
   - Example:
     ```html
     <link rel="stylesheet" href="style.css">
     ```

