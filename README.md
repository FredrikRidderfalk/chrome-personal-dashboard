# Chrome Personal Dashboard

## Table of contents

- [Overview](#overview)
  - [The goal](#the-goal)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The goal

Users should be able to:

- [x] Install this dashboard as an extension for their Chrome browser
- [x] See a new background each time they open a new tab
- [x] See a default image if the Unsplash API data fails to load
- [x] See the local weather conditions if user grants location access
- [x] See a description of the photo if available
- [x] See current price of their favorite cryptocurrency, including most recent 24H highest and lowest prices

### Screenshot

![](./screenshot.png)

## My process

- I carefully read through API documentation and include preferred data.
- I maintained high contrast ratios (13.1:1, 7.74:1) throughout the website, passing all WCAG tests. Tested using [WebAIM](https://webaim.org/resources/contrastchecker/?fcolor=000000&bcolor=16DFBD).

### Built with

- Semantic HTML5 markup
- CSS3
- Flexbox
- JavaScript (ES6)
- JSON

### What I learned

- WCAG 2.0 level AA requires a contrast ratio of at least 4.5:1 for normal text and 3:1 for large text. WCAG 2.1 requires a contrast ratio of at least 3:1 for graphics and user interface components (such as form input borders). WCAG Level AAA requires a contrast ratio of at least 7:1 for normal text and 4.5:1 for large text. Large text is defined as 14 point (typically 18.66px) and bold or larger, or 18 point (typically 24px) or larger.

- How to read through API documentation to fetch only the relevant data.

### Continued development

I want to implement a drop-down selection box that lets users choose what cryptocurrency they want to display.

### Useful resources

- [Nu Html Checker](https://validator.w3.org/nu/) - I ran my index.html through this conformance checker to catch any unintended mistakes.
- [CSS Validation Service](https://jigsaw.w3.org/css-validator/) - I ran my style.css through this conformance checker to catch any unintended mistakes.

## Author

- Website - [My Personal Portfolio](https://fredrikridderfalk.github.io/)
- GitHub - [@FredrikRidderfalk](https://github.com/FredrikRidderfalk)
- Twitter - [@Ridderfalk](https://twitter.com/Ridderfalk)

## Acknowledgments

My acknowledgements go out to the team at Scrimba. Enrolling in your courses made this project possible. I learned a lot for this project from Ania Kubow.
