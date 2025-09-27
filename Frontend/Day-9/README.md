# HTML Images Project

This project demonstrates the use of **HTML images** and related
concepts along with CSS styling.\
It includes practical examples of image insertion, floating, tables,
background images, responsive picture elements, and favicon usage.

------------------------------------------------------------------------

## 📌 Topics Learned

### 1. Basic HTML Structure

-   `<!DOCTYPE html>`: Defines the document type as HTML5.
-   `<html>`, `<head>`, `<body>`: Basic HTML skeleton.
-   `<title>`: Sets the title of the web page (shown on browser tab).

### 2. CSS Basics

-   `body { margin: 0; padding: 0; }`: Removes default margin/padding.
-   `font-family`: Sets clean and modern fonts.
-   `background-color`: Gives background color to the page.

### 3. Fixed Header with Gradient

-   Used `<header>` for the page heading.

-   Applied **linear gradient background** with CSS:

    ``` css
    background: linear-gradient(135deg, #ff7e5f, #feb47b);
    ```

-   `position: fixed; top: 0; left: 0; width: 100%;`: Keeps header
    always visible.

-   Added **box-shadow** for depth.

### 4. Navigation Bar

-   Created navigation with `<nav>` and `<a>` links.
-   Used CSS `hover` effect for smooth interactivity.

### 5. Image Insertion

-   `<img src="image.png" alt="text">`: Basic image insertion.
-   `alt` attribute provides fallback text.

### 6. Image Floating

-   `float: left;` and `float: right;` allow images to align beside
    text.

### 7. Tables in HTML

-   Created a table of **image file formats** using `<table>`,
    `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`.
-   Used CSS:
    -   `border-collapse: collapse;`: Merges cell borders into a single
        line.
    -   `tr:nth-child(even)`: Gives zebra-stripe effect for readability.
    -   `tr:hover`: Highlights row on hover.

### 8. Background Images

-   Applied background image with CSS:

    ``` css
    background-image: url('street-view.jpg');
    background-size: cover;
    background-position: center;
    ```

-   Wrapped inside a `<div>` for proper height & width.

### 9. Picture Element

-   Learned how to use `<picture>` for **responsive images**:

    ``` html
    <picture>
        <source media="(min-width: 650px)" srcset="large.png">
        <source media="(min-width: 465px)" srcset="medium.png">
        <img src="fallback.png">
    </picture>
    ```

-   Helps browsers pick best image depending on screen size.

### 10. Favicon

-   Added favicon using:

    ``` html
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    ```

-   Appears next to the page title in the browser tab.

------------------------------------------------------------------------

## 🎨 CSS Features Used

-   **Gradient backgrounds**
-   **Hover effects**
-   **Fixed positioning**
-   **Box shadows**
-   **Responsive layout**

------------------------------------------------------------------------

## 🚀 Conclusion

By building this project, I learned how to: 1. Insert and style images.
2. Float images alongside text. 3. Create beautiful tables with CSS
effects. 4. Use background images effectively. 5. Implement responsive
images with `<picture>`. 6. Add a favicon to a webpage.

This small project improves both **HTML and CSS** skills and is a great
step in mastering frontend development.
