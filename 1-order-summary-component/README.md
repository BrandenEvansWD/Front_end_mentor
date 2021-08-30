# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](https://ibb.co/PG5Y8LQ)

### Links

- Solution URL: (https://github.com/BrandenEvansWD/Front_end_mentor/tree/main/1.%20order-summary-component-main)

- Live Site URL: (https://front-end-mentor-project-1.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This is my first project since I began learning scss, that I've coded entirely on my own. Some issues I came across were specifically scss related; naming and nesting elements in a structured manner.

I also came across some issues with center the element directly in the middle of a page while still maintaining flexable margins outside of the card container.

Another interest thing I learned was to push an element over in a row of multiple elements with a simple bit of code:

```css
 &--cost {
      font-weight: 700;
      width: 8rem;
      margin-right: auto;
      text-align: center;

      @media (max-width: 500px) {
        margin-right: 0;
      }
```

### Continued development

I would really like to just generally learn more scss, along with being able to consistantly space elements in a meaningful way.

### Useful resources

- [Stack Overflow](https://stackoverflow.com/questions/41438699/text-align-center-and-align-items-center-not-working-horizontally/41438786) - This is what ultimately led me to finding a solution for my margin spacing issues.

## Author

- Website - [Branden Evans](https://wwww.brandenevans.me)
- Frontend Mentor - [@BrandenEvansWD](https://www.frontendmentor.io/profile/BrandenEvansWD)

## Acknowledgments

I would to thank the creators of frontendmentor.io for a wonderful tool for aspiring developers like myself.
