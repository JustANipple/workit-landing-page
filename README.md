# Frontend Mentor - Workit landing page solution

This is a solution to the [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/screenshot_desktop.png)

### Links

- Solution URL: [Solution](https://github.com/JustANipple/workit-landing-page/blob/main/index.html)
- Live Site URL: [Live site](https://justanipple.github.io/workit-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Making the purple curve was a challenge. At first i tried drawing an SVG, but i noticed that on mobile devices you could see a line separating the background and SVG. Then i discovered clip-path and with that i made an ellipse that can take parameters to draw the shape i wanted

This is the rule i used for header and features curve

```css
.header::before, .features::before {
    clip-path: ellipse(60% 50% at center);
}
```

## Author

- Frontend Mentor - [@JustANipple](https://www.frontendmentor.io/profile/JustANipple)