# HTML Quotation and Citation Examples

This project demonstrates how to use different **HTML quotation and
citation tags** such as `<blockquote>`, `<q>`, `<abbr>`, `<address>`,
`<cite>`, and `<bdo>`. Each tag has its own purpose, and the code shows
both examples and explanations.

------------------------------------------------------------------------

## 📖 What's Covered

### 1. `<blockquote>` -- Block Quotation

-   Used for longer quotations, often displayed as an indented block.\
-   Can include the `cite` attribute to specify the source of the
    quotation.

**Example:**

``` html
<blockquote cite="http://www.worldwildlife.org/who/index.html">
  For 60 years, WWF has worked to help people and nature thrive...
</blockquote>
```

------------------------------------------------------------------------

### 2. `<q>` -- Inline Quotation

-   Used for short, inline quotes.\
-   Browsers usually add quotation marks automatically.

**Example:**

``` html
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```

------------------------------------------------------------------------

### 3. `<abbr>` -- Abbreviation or Acronym

-   Defines abbreviations and acronyms.\
-   The `title` attribute provides the full form when hovered.

**Example:**

``` html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

------------------------------------------------------------------------

### 4. `<address>` -- Contact Information

-   Specifies contact details for the author/owner of a document.\
-   Typically displayed in *italic* by browsers.

**Example:**

``` html
<address>
  Written by John Doe.<br>
  Visit us at:<br>
  Example.com<br>
  Box 564, Disneyland<br>
  USA
</address>
```

------------------------------------------------------------------------

### 5. `<cite>` -- Work Title

-   Used to define the title of a creative work (book, song, movie,
    etc.).\
-   Browsers usually display it in *italic*.

**Example:**

``` html
<p><cite>The Great Gatsby</cite> is a classic novel.</p>
```

------------------------------------------------------------------------

### 6. `<bdo>` -- Bi-Directional Override

-   Stands for **Bi-Directional Override**.\
-   Forces text direction (`rtl` = right to left, `ltr` = left to
    right).

**Example:**

``` html
<bdo dir="rtl">This text will be written from right to left</bdo>
```

------------------------------------------------------------------------

## 🎨 Styling

-   The page uses a simple **container-based layout** with:
    -   `antiquewhite` background\
    -   `coral` headings\
    -   Borders, rounded corners, and shadows for better readability

------------------------------------------------------------------------

## 📌 Purpose

This project is a **learning exercise** to understand and practice
**HTML quotation and citation elements**.
