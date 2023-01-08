# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Desktop](./images/result-desktop.png)
![Mobile](./images/result-mobile.png)

### Links

- Solution URL: [https://github.com/R3B3-888/single-price-grid-component](https://github.com/R3B3-888/single-price-grid-component)
- Live Site URL: [https://r3b3-888.github.io/single-price-grid-component](https://r3b3-888.github.io/single-price-grid-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

I learned more about css grid in the main and flexbox the body tag.
I consolidated my knowledge on media query.

I'm proud of this code because it is very little:

```css
@media all and (max-width: 640px) {
  main {
    display: flex;
    flex-direction: column;
    width: 80vw;
  }
  
  .section-bot-left {
    border-bottom-left-radius: 0;
  }
  
  .section-bot-right {
    border-bottom-left-radius: 2%;
  }
}
```

### Continued development

It can be improved on the width 100% on the cta. On centering the per month text and adjusting the different heights of
each section.

### Useful resources

- [Mdn docs](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height) - This helped me for line spacing reason. 

## Author

- Website - [Alexis](https://r3b3.github.io)
- Frontend Mentor - [@R3B3-888](https://www.frontendmentor.io/profile/R3B3-888)
