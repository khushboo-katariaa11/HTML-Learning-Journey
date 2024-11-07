# HTML Learning Journey

This repository documents my progress and learning in HTML, organized by levels to build a solid foundation.

---

### Table of Contents

1. [Level 1 - HTML Basics](#level-1---html-basics)
2. [Level 2 - Intermediate HTML](#level-2---intermediate-html)
3. [Level 3 - Forms and Tables](#level-3---forms-and-tables)

---

## Level 1 - HTML Basics

- **HTML Structure**: Set up the HTML document structure using `<!DOCTYPE>`, `<html>`, `<head>`, and `<body>` tags.
- **Headings**: Learned different heading levels (`<h1>` to `<h6>`).
- **Paragraphs**: Created paragraphs using the `<p>` tag.
- **Text Formatting**: Practiced basic text styling with:
  - **Bold**: `<b>bold text</b>`
  - **Italic**: `<i>italic text</i>`
  - **Underline**: `<u>underlined text</u>`
  - **Line Break**: `<br>` for new lines

- **Lists**:
  - **Ordered Lists**: Used `<ol>` and `<li>` tags for numbered lists.
  - **Unordered Lists**: Created bullet-point lists with `<ul>` and `<li>`.

- **Links and Images**:
  - **Anchor Tags**: Added hyperlinks using `<a href="#">link text</a>`.
  - **Image Tag**: Displayed images with `<img src="URL" alt="description">`.

---

## Level 2 - Intermediate HTML

- **HTML Entities**:
  - Used entities like `&hearts;` for ♥, `&bigstar;` for ★, and `&amp;` for &.

- **Block and Inline Elements**:
  - **Block Elements**: Practiced using `<div>`, `<p>`, `<h1>`, and `<hr>`.
  - **Inline Elements**: Used `<span>`, inline links, and images within block elements.

- **Superscript and Subscript**:
  - **Example Usage**:
    - Pythagorean Theorem: a<sup>2</sup> + b<sup>2</sup> = c<sup>2</sup>
    - Chemical Formulas: H<sub>2</sub>O and C<sub>6</sub>H<sub>12</sub>O<sub>6</sub>

- **Emmet Abbreviations**:
  - **Parent-Child Relation**: `header>nav>ul>li*2`
  - **Sibling Relation**: `div>p+img+a`
  - **Multiplication**: `ul>li*4`

---

## Level 3 - Forms and Tables

- **Tables**:
  - **Basic Table Structure**: Created tables using `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>`.
  - **Table Captions**: Added captions to tables with `<caption>`.
  - **Advanced Table Layouts**: Used `rowspan` and `colspan` to merge cells.

  **Example Table**:
  ```html
  <table>
    <caption>Food Menu</caption>
    <thead>
      <tr><th>Item</th><th>Price</th></tr>
    </thead>
    <tbody>
      <tr><td>Frooti</td><td>10 INR</td></tr>
      <!-- More rows -->
    </tbody>
  </table>
### Forms

- **Form Basics**: Set up forms using `<form action="URL">`.
- **Input Types**: Practiced with text, password, number, and time inputs.
- **Buttons**: Included `submit`, `reset`, and custom action buttons.
- **Radio Buttons and Checkboxes**: Used `<input type="radio">` and `<input type="checkbox">`.
- **Dropdowns**: Created select menus with `<select>` and `<option>`.
- **Text Area**: Added feedback sections using `<textarea>`.
