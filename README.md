# Frontend Mentor - Recipe page solution

This is my solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor helps you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

![](./design/desktop-design.jpg)

- Live Site URL:(https://recipepagesolutionfrontendmentor.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow
- Custom Fonts (Young Serif, Outfit)

### What I learned

While this project appeared simple at first glance, it presented some interesting challenges that helped me enhance my CSS skills. Here are some key learnings:

- Improved my understanding of CSS Grid for creating responsive layouts, particularly in the nutrition section
- Learned to effectively implement custom fonts using @font-face:

```css
@font-face {
  font-family: "Young Serif";
  src: url("/assets/fonts/young-serif/YoungSerif-Regular.ttf") format("truetype");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}
```

- Practiced creating clean, maintainable CSS using custom properties:

```css
:root {
  --bg-color: #f3e5d8;
  --mainCard-bg-color: #fff;
  --sectionFirst-bg-color: #fff7fc;
  /* other variables */
}
```

- Enhanced my skills in responsive design and mobile optimization
