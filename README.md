# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot](./images/screenshots/Screenshot%202025-09-16%20at%204.59.56 PM.png)

### Links

- Solution URL: [GitHub Repo](https://github.com/ajkendal/blog-preview-card)
- Live Site URL: [Live](https://ajkendal.github.io/blog-preview-card)
- Frontend Mentor Submission URL: [Frontend Mentor]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- GitHub Pages

### What I learned

While building this project, I deepened my understanding of modern CSS techniques and accessibility best practices. I learned how to leverage CSS custom properties for consistent theming, use CSS Grid for flexible layouts, and ensure my markup is accessible to all users.

For example, I used CSS variables to keep my color palette and spacing consistent:

```css
:root {
  --clr-yellow: hsl(47, 88%, 63%);
  --spacing-300: 1.5rem;
}

.token {
  background-color: var(--clr-yellow);
  padding: var(--spacing-300);
}
```

I also used CSS Grid to center the card and create a responsive layout:

```css
body {
  display: grid;
  place-items: center;
  grid-template-columns: 2fr 327px 2fr;
}
```

To improve accessibility, I paid attention to heading order, used descriptive alt text, and added ARIA roles:

```html
<main class="card" role="main" aria-label="Blog preview card">
  <!-- content -->
</main>
```

## Author

- Website - [Amanda J Kendal-Brown](https://ajkendal.github.io/)
- LinkedIn - [@akendalb](https://www.linkedin.com/in/akendalb)
- GitHub - [@ajkendal](https://github.com/ajkendal/)
- Frontend Mentor - [@ajkendal](https://www.frontendmentor.io/profile/ajkendal)
