# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot%20from%202024-03-01%2016-48-36.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/product-preview-card-GTdeGOdb_f)
- Live Site URL: [Add live site URL here](https://transcendent-macaron-8301ab.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<picture>
  <source
    media="(max-width: 600px)"
    srcset="./images/image-product-mobile.jpg"
  />
  <source
    media="(min-width: 601px)"
    srcset="./images/image-product-desktop.jpg"
  />
  <img
    src="images/image-product-desktop.jpg"
    alt="perfume"
    class="mobile-img"
  />
</picture>
```

```css
.card-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
```

### Continued development

1. Responsive Techniques.
2. Layout Dimensions.

### Useful resources

- [Picture Tag](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - This helped me for make responsive images in both desktop and mobile layout. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@ahmed-shahat](https://www.frontendmentor.io/profile/ahmed-shahat)
