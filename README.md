# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked
- **Bonus**: Complete the challenge without using JavaScript

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/faq-accordion-card-rXNAkSj8Yf](https://www.frontendmentor.io/solutions/faq-accordion-card-rXNAkSj8Yf)
- Live Site URL: [https://seranela.github.io/faq-accordion-card/](https://seranela.github.io/faq-accordion-card/)

## My process

### Built with

- HTML5
- CSS
- Flexbox
- Mobile-first workflow

### What I learned

Achieving interaction without using JavaScript and using only CSS selectors.

Background image positioning offsets (background-position: 3 or 4-value setting) is bit of a tricky thing to understand. Instead of offseting from named vales (left, center, etc), use the equivalent numerical value for offsetting or use a calc().

I personally agree that using a &lt;dl&gt; definition list seems more semantic for an FAQ but setting it up for accessibility without using JavaScript (to get the bonus challenge) was super tricky to get 100 score in accessibility and frankly becoming verbose. I ended up using a &lt;details&gt; element and the resulting code was so much cleaner and easier to work with. It also passed accessibility tests in Firefox, Chrome (score of 100) and WebAIM.

Note: I attempted this without looking at existing solutions to see if I could figure it out myself.

### Continued development

Continue experimenting with background image properties.

## Author

- Frontend Mentor - [@seranela](https://www.frontendmentor.io/profile/seranela)