# HTML Styles - CSS Tutorial

This project is a simple **HTML tutorial** demonstrating different ways of using CSS in HTML.  
It is designed to help beginners understand how CSS works with practical examples.

---

## 📖 What is CSS?
CSS (**Cascading Style Sheets**) is used to format the layout of a webpage.  
With CSS, you can control:
- Colors
- Fonts
- Text sizes
- Spacing between elements
- Positioning and layout
- Backgrounds
- Responsive design for different devices

**Tip:** The word *cascading* means that styles applied to a parent element will also apply to its child elements (unless overridden).

---

## 🎨 Ways to Use CSS
1. **Inline CSS**  
   Applied directly in an element using the `style` attribute.  

   ```html
   <p style="color: red; font-size: 20px;">This is inline CSS</p>
   ```

2. **Internal CSS**  
   Written inside a `<style>` tag in the `<head>` section.  

   ```html
   <style>
     body { background-color: powderblue; }
     h1 { color: blue; }
   </style>
   ```

3. **External CSS**  
   Written in a separate `.css` file and linked using `<link>`.  

   ```html
   <link rel="stylesheet" href="styles.css">
   ```

   Example `styles.css` file:

   ```css
   body {
     background-color: powderblue;
   }
   h1 {
     color: blue;
   }
   p {
     color: red;
   }
   ```

---

## 🖌 CSS Properties Demonstrated
- **Colors, Fonts and Sizes**
- **Borders**
- **Padding (space inside the border)**
- **Margins (space outside the border)**

Example:

```css
p {
  border: 2px solid powderblue;
  padding: 30px;
  margin: 50px;
}
```

---

## 🚀 How to Use
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Open the `index.html` file in your browser.

3. Explore the examples and learn CSS step by step!

---

## 📂 Project Structure
```
.
├── index.html   # Main tutorial page with examples
├── styles.css   # Example external stylesheet
└── README.md    # Documentation
```

---

## ✨ Author
Made with ❤️ by **Abhishek Tomar**
