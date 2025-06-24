# Frontend Mentor - 3-column preview card component solution by Michael

This is my solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). This project was a practical refresher in layout design, responsiveness, and maintaining clean structure across multiple screen sizes.

## Table of contents

* [Overview](#overview)

  * [The challenge](#the-challenge)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My process](#my-process)

  * [Built with](#built-with)
  * [What I learned](#what-i-learned)
* [Author](#author)

---

## Overview

### The challenge

Users should be able to:

* View the optimal layout depending on their device's screen size
* See hover states for interactive elements

### Screenshot

![Mobile Layout Screenshot](./screenshots/3-column%20preview%20card%20component%20Mobile%20Screenshot.png)
![Desktop Layout Screenshot](./screenshots/3-column%20preview%20card%20component%20Desktop%20Screenshot.jpg)

> *Captured using the Chrome DevTools Command Menu with `Ctrl + Shift + P` → "Capture full size screenshot".*

### Links

* **Live Site URL**: [https://your-live-site-url.com](https://your-live-site-url.com)

---

## My process

### Built with

* Semantic HTML5 markup
* CSS custom properties
* CSS Grid and Flexbox for layout
* Responsive media queries

---

### What I learned

#### `min-height: calc(100vh - 50px);`

One key CSS lesson today was using:

```css
min-height: calc(100vh - 50px);
```

This ensures the main content fills the screen height minus the height of the footer (which was roughly 50px). This adjustment prevents the footer from sitting awkwardly beside centered content when using Flexbox or Grid layouts for vertical centering. It allowed the page to remain scroll-free on larger screens while still accommodating the footer.

#### Chrome DevTools Command Menu

I also learned how to use the Chrome **Command Menu** to capture a full-page screenshot of the mobile view:

* Open DevTools with `Ctrl + Shift + I`
* Toggle mobile view with `Ctrl + Shift + M`
* Open Command Menu with `Ctrl + Shift + P`
* Type and select **"Capture full size screenshot"**

This was especially useful for generating high-quality screenshots that capture the entire vertical layout.

---

## Author

* Frontend Mentor – [@michaelo-o](https://www.frontendmentor.io/profile/michaelo-o)

