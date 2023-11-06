# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Challenge to build out the FAQ accordion card and get it looking as close to the design as possible. No Javascript to be used, just HTML and CSS.

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./Screenshot-Accordion-Card.png)

### Links

- Solution URL: https://github.com/Gunner40/FAQ-accordion-card
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

How to write media queries for min and max width at the same time.
How to hide an element by setting its max-height to 0 and overflow property to hidden.
How to make an element re-display by re-setting its max-height to a desired value greater than 0.
How to changed styles on an element when an different element (input) is checked using .accordion**item input:checked ~ .accordion**content.
Used the + and ~ css selectors. "h1 + p" will only select only THE FIRST p that is immediately preceded by a h1. "h1 ~ p" will select ALL the p siblings preceded by a h1.

```css
@media only screen and (min-width: 650px) and (max-width: 1200px);

.accordion__item input:checked ~ .accordion__content {
  max-height: 200px;
}
```

## Author

- Name - Paul Ryan
- Frontend Mentor - [@Gunner40](https://www.frontendmentor.io/profile/Gunner40)
