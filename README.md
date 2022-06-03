# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [My Solution](https://www.frontendmentor.io/solutions/stats-preview-card-component-by-wafferu-1nU2wAA3jC)
- Live Site URL: [The Live Site](https://mellifluous-queijadas-6812c5.netlify.app/)

## My process

I structure the html of the webpage first. Then, I add the styles and use Mobile-first workflow. After that, I work on how to make the webpage responsive on different device's screen size.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

What I learned on this project:

- How to make the image have a color

```html
<div class="statsPrevCardCompDiv">
  <!-- For this -->
  <img src="./images/image-header-mobile.jpg" alt="image-header-desktop" />
</div>
```

```css
.statsPrevCardCompDiv:first-child {
  background: hsl(277, 64%, 61%); /* This */
  border-radius: 0.5rem 0.5rem 0rem 0rem;
}

.statsPrevCardCompDiv:first-child img {
  width: 100%;
  height: 100%;
  border-radius: 0.5rem 0.5rem 0rem 0rem;
  opacity: 0.6; /* This */
}
```

### Continued development

I will continue to work on my fundamentals.

### Useful resources

- [Coloring the Image](https://css-tricks.com/snippets/css/monotone-image-css/) - This helped me for adding color to the image.

## Author

- Frontend Mentor - [@wafferu](https://www.frontendmentor.io/profile/wafferu)

## Acknowledgments

N/A
