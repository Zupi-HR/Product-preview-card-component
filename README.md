# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop design screenshot](desktop-design.png)
![Mobile design screenshot](mobile-design.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Zupi-HR/Product-preview-card-component)
- Live Site URL: [Add live site URL here](https://zupi-hr.github.io/Product-preview-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This project was a great opportunity to practice responsive design using a mobile-first workflow. I primarily used Flexbox for content alignment within the card, but I used CSS Grid for the main two-column layout on desktop. This helped me understand the strengths of each tool.

For example, switching to a two-column grid on larger screens was straightforward with a simple media query:

```css
@media (min-width: 492px) {
  .product-card {
    grid-template-columns: 1fr 1fr;
  }
}
```

### Continued development

I need to continue improving my skills with CSS Grid. There's a lot I still don't know, as I have mostly used Flexbox.

## Author

- Website - [Zupi](https://github.com/Zupi-HR)
- Frontend Mentor - [@Zupi-HR](https://www.frontendmentor.io/profile/Zupi-HR)
# Product-preview-card-component
# Product-preview-card-component
