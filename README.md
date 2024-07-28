# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). 

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

The challenge is to build out this blog preview card and get it looking as close to the design as possible using any available tools.

Your users should be able to:

- See hover and focus states for all interactive elements on the page (I added a few just for fun)

**Additional challenge:** The font sizes in this project are slightly smaller in the mobile layout. Find a way to reduce font size for smaller screens without using media queries.

### Screenshot

![Screenshot 1440px](/screenshot.png)
[Click here to see a cropped screenshot at 375px](/assets/screenshot-mobile.png)

### Links

- Solution URL: [See my solution on GitHub](https://github.com/jguleserian/FMC-Blog-Preview-Card)
- Live Site URL: [See my solution live](https://jguleserian.github.io/FMC-Blog-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library


### What I learned

This project included the additional challenge of finging a way to reduce font size for smaller screens without using media queries. So, I began to investigate methods. What I landed on was the `clamp` parameter that allows a maximum, minimum, and optimal measurement. This solved the issue of trying to use percentages or view widths to try and scale down the font. Doing so is difficult because the page size (and subsequent margin around the `<main>` container) and/or the parent container of the object you are trying to reduce both change dynamically. `clamp` works like having a max-width and min-width for containers as well, so it was pretty handy. 

### Continued development

This is my second project for the Frontend Learning Path. I will continue to work through the path to move on to the next one. I also want to perfect the ability to make more responsibe websites. This project has given me an additional step toward that goal.

### Useful resources

- [MDN web docs: "clamp()](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp) - This resource spells out the use and compatibility of the `clamp()` parameter.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)



