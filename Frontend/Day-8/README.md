# HTML Links Tutorial

This project demonstrates how HTML links work, including clickable text, images, email links, and buttons as links. It also explains the difference between relative and absolute URLs and shows how to make pages responsive.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Examples of Links](#examples-of-links)
3. [Target Attribute](#target-attribute)
4. [Relative vs Absolute URL](#relative-vs-absolute-url)
5. [Using Images as Links](#using-images-as-links)
6. [Email Links](#email-links)
7. [Buttons as Links](#buttons-as-links)
8. [Responsive Design](#responsive-design)

---

## Introduction

HTML links (hyperlinks) allow users to navigate from one page to another or to external websites. The `<a>` tag is used with an `href` attribute specifying the link's destination.

---

## Examples of Links

```html
<a href="https://google.com/" target="_parent">Visit Google</a>
<a href="https://facebook.com/" target="_blank">Visit Facebook</a>
<a href="https://instagram.com/" target="_blank">Visit Instagram</a>
<a href="https://abhishek-09-tomar.github.io/Portfolio-Website/" target="_top">Visit Portfolio</a>
```

- `href`: destination URL
- `target`: where the link opens

---

## Target Attribute

- `_self`: opens in the same page (default)
- `_blank`: opens in a new tab
- `_parent`: opens in parent frame
- `_top`: opens in the full window, removing frames

---

## Relative vs Absolute URL

### Relative URL

Points to a file relative to the current page.

```html
<a href="about.html">about.html</a>
<a href="assets/model.jpg">assets/model.jpg</a>
```

### Absolute URL

Full address including protocol and domain.

```html
<a href="https://www.google.com">https://www.google.com</a>
<a href="https://www.wikipedia.org/images/logo.png">Logo Image</a>
```

---

## Using Images as Links

```html
<a href="https://pixabay.com/" target="_blank">
    <img src="https://cdn.pixabay.com/photo/2024/11/02/17/29/city-9169729_1280.jpg" alt="Landscape">
</a>
```

Clicking the image redirects to the link.

---

## Email Links

```html
<a href="mailto:someone@example.com">Send Email</a>
```

Opens the email client.

---

## Buttons as Links

```html
<button onclick="window.location.href='https://abhishek-09-tomar.github.io/Portfolio-Website/'">
    Abhishek Tomar
</button>
```

---

## Responsive Design

- Flexbox layout
- Max-width and percentage widths
- Media queries adjust fonts, padding, and margins for smaller screens

---

**Author:** Abhishek Tomar  
**Portfolio:** [https://abhishek-09-tomar.github.io/Portfolio-Website/](https://abhishek-09-tomar.github.io/Portfolio-Website/)
