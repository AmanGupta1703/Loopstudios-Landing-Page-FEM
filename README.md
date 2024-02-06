# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./output/desktop-preview.png)

### Links

- Solution URL: [https://github.com/AmanGupta1703/Loopstudios-Landing-Page-FEM](https://your-solution-url.com)
- Live Site URL: [https://loopstudios-landing-page-fem.vercel.app/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
.card {
  cursor: pointer;
  background-position: center center;
  background-size: cover;
  width: 100%;
  height: 18vh;
  -webkit-transition: all 0.5s ease;
  transition: all 0.5s ease;
  overflow: hidden;
  position: relative;
}
.card::before {
  -webkit-transition: all 0.5s ease;
  transition: all 0.5s ease;
}
.card:hover::before {
  content: '';
  background-color: rgba(255, 255, 255, 0.8);
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;
}
.card:hover .card__title {
  color: var(--color-black);
}
.card:not(:last-child) {
  margin-bottom: 2rem;
}
```

### Continued development

### Useful resources

- [MDN - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

## Author

- Website - [Loopstudios Landing Page](https://loopstudios-landing-page-fem.vercel.app/)
- Frontend Mentor - [@AmanGupta1703](https://www.frontendmentor.io/profile/AmanGupta1703)
- Twitter - [@thekunalgupta17](https://www.twitter.com/thekunalgupta17)