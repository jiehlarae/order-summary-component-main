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

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./images/desktop%20version.png)
![](./images/mobile%20version.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I'm starting to grasp the concept of adjusting width and height. I've discovered that when you establish specific height and width values and later adapt them for smaller screens using percentages, the adjustment is relative to those original sizes. For instance, if I initially set the card's width to 450px, on smaller screens, I might adjust it to be 90% of that original 450px width.


```css
.card {
  width: 450px;
}

@media (max-width:500px) {
  .card {
    max-width: 90%;
  }
}
```

### Continued development

I'm currently finding width and height a bit confusing, but I am committed to working on it and dedicating more time to practice and get better on it.

### Useful resources

- [Resource 1](https://www.udemy.com/course/the-web-developer-bootcamp/learn/lecture/22587506#overview) - I'm currently taking Colt Steele Web Developer Bootcamp, and I couldn't recommend it enough. So, check it out!

## Author

- Website - [@jiehlaraee](https://github.com/jiehlarae)
- Frontend Mentor - [@jiehlarae](https://www.frontendmentor.io/profile/jiehlarae)
- Twitter - [@JiehlaDacara](https://twitter.com/JiehlaDacara)