# Lazy-Day Mug Cake

**Lazy-Day Mug Cake** is a responsive, single-page HTML/CSS/JavaScript recipe app that walks users through the ingredients and preparation steps for a quick microwave mug cake. It uses simple DOM interactions, semantic HTML, responsive CSS, and Font Awesome icons for a polished front-end experience.

---

## Features

- **Semantic HTML structure** with `header`, `section`, and `footer` tags
- **Responsive layout** with a media query for smaller screens
- **Font Awesome icons** for visual enhancement (`fa-spoon`, `fa-check-circle`)
- **JavaScript interactivity** using `onmouseover` and `onmouseout` events to animate icons
- **CSS styling** for consistent typography and a clean layout
- **Single image preview** of the dessert for visual appeal

---

## Technologies Used

- **HTML5**: For semantic structure and layout
- **CSS3**: Custom styling and responsive design
- **JavaScript**: DOM manipulation for interactive icons
- **Font Awesome**: Iconography for UI enhancement

---

## Elements Breakdown

### HTML

- `<!DOCTYPE html>` for HTML5 declaration
- `<header>`, `<section>`, `<footer>` for semantic structure
- `<ul>` and `<ol>` lists for ingredients and preparation steps
- `<img>` for recipe image
- `<i>` Font Awesome icons with `class="fa"` and appropriate icon names
- Inline JavaScript events: `onmouseover`, `onmouseout`

### CSS

- Global styles for `body`, `h1`, `h2`, and `footer`
- ID-based container styling: `#container`
- Responsive media query for screens `<768px`
- Font and color customization
- `text-transform`, `font-weight`, `padding`, `margin`, and `width` used throughout

### JavaScript

- Functions for enlarging/reducing icon size:
  ```js
  function ingredientsHover() {
    document.getElementById("ingredients").style.fontSize = "300%";
  }

  function ingredientsNormal() {
    document.getElementById("ingredients").style.fontSize = "100%";
  }
Similar functions for the preparation icon

Basic, inline <script> at the bottom of the HTML
