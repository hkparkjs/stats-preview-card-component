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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot-desktop.png)
![](./screenshot-mobile.png)


### Links

- Solution URL: [https://github.com/hkparkjs/stats-preview-card-component](https://github.com/hkparkjs/stats-preview-card-component)
- Live Site URL: [https://park-stats-preview-card-component.netlify.app/](https://park-stats-preview-card-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned
 - How to apply CSS custom variables
```css
/* define variables */
:root {
  --very-dark-blue: hsl(233, 47%, 7%);
  --dark-desaturated-blue: hsl(244, 38%, 16%);
  --soft-violet: hsl(277, 64%, 61%);
  --white: hsl(0, 0%, 100%);
  --main-paragraph-white: hsla(0, 0%, 100%, 0.75);
  --stat-headings-white: hsla(0, 0%, 100%, 0.6);
}

/* usage example */
body {
  (...)
  background-color: var(--very-dark-blue);
}
```

 - How to change image color
```css
.image-area {
  (...)
  background-color: var(--soft-violet);
}

.image-area img {
  (...)
  mix-blend-mode: multiply;
  opacity: 70%;
}
```

### Useful resources

- [CSS custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - This helped me for writing code simply.
- [CSS mix-blend-mode property](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - This helped me for changing image color.
## Author

- Frontend Mentor - [@hkparkjs](https://www.frontendmentor.io/profile/hkparkjs)
