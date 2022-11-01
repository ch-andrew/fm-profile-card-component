# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

A simple QR Code Card Component using HTML and Less CSS 

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Github Repo](https://github.com/ch-andrew/fm-profile-card-component)
- Live Site URL: [Github Page](https://ch-andrew.github.io/fm-profile-card-component/)

## My process

I started with simple html and less css to follow the style-guide. I have restarted this project for 3 times because I was so confused on how to make the card using 1. display:flex and 2. position:relative but then I finally started using css grid and I could finished the component using CSS Grid. However, my biggest obstacle was trying to figure out how to style/design the background pattern element to be exactly the same with requested design. At this point of writing, I'm still confused/ not able to correctly designed the background element.

### Built with

- Semantic HTML5 markup
- LESS CSS
- CSS custom properties
- Flex & Grid


### What I learned

In this project I have learn how to use css grid better and I'm quite happy with how css grid works. 

```css
.card {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 2fr 2fr 1fr;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  ...
}
.card-img {
  grid-area: 1 / 1 / 3 / 2;
  ...
}
.card-caption {
  grid-area: 2 / 1 / 3;
  ...
}
.card-stats {
  grid-area: 3 / 1 / 4 / 2;
  ...
}
```

## Author

- Website - [ch-andrew](https://github.com/ch-andrew)
- Frontend Mentor - [ch-andrew](https://www.frontendmentor.io/profile/ch-andrew)

## Acknowledgments

Thank you [Frontend Mentor](https://www.frontendmentor.io) for this challenges that can help me improve my frontend skills

