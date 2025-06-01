# Frontend Mentor - Advice generator app solution

This is a solution to the [Advice generator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents
- [Frontend Mentor - Advice generator app solution](#frontend-mentor---advice-generator-app-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)

## Overview
### The challenge
Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Generate a new piece of advice by clicking the dice icon

### Screenshot
![](./screenshot.jpg)

### Links
- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- JavaScript

### What I learned
I learned how to generate random quotes using JavaScript and display them on the page. I also learned how to use CSS to create a visually appealing design.

javascript
let cube = document.querySelector(".cube-container");
let id = document.querySelector(".id");
let quoteDisplay = document.querySelector(".quotes");
let currentQuoteIndex = 0;

cube.addEventListener("click", () => {
  currentQuoteIndex = Math.floor(Math.random() * quotes.length);
  quoteDisplay.innerText = "${quotes[currentQuoteIndex]}";
  id.innerText = currentQuoteIndex + 1;
});


*Continued development*
I want to continue improving my JavaScript skills and learn how to use more advanced features like async/await and promises. I also want to learn more about accessibility and how to make my websites more user-friendly.

*Useful resources*
- https://developer.mozilla.org/en-US/ - This website provides excellent documentation and resources for web developers.
- https://www.w3schools.com/ - This website provides tutorials, examples, and reference materials for web development.

*Author*
- Frontend Mentor - https://www.frontendmentor.io/profile/yourusername
- Twitter - https://www.twitter.com/yourusername

*Acknowledgments*
I would like to thank Frontend Mentor for providing the design and challenge.

