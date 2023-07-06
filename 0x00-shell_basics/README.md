# Frontend Mentor - Age calculator app solution

This is a solution to the [Age calculator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/age-calculator-app-dF9DFFpj-Q). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)




## Overview

The goal was to replicate the webpage with my style of approach

### The challenge

Users should be able to:

- View an age in years, months, and days after submitting a valid date through the form
- Receive validation errors if:
  - Any field is empty when the form is submitted
  - The day number is not between 1-31
  - The month number is not between 1-12
  - The year is in the future
  - The date is invalid e.g. 31/04/1991 (there are 30 days in April)
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: See the age numbers animate to their final number when the form is submitted



## My process


As part of my readme process, I worked extensively with HTML, CSS, and JavaScript to create a visually appealing and interactive user experience. HTML provided the structure and content of my website, while CSS was used to style and format it according to my design preferences.

JavaScript was used to add interactivity to my website, allowing users to interact with the content and perform various actions.

Throughout the development process, I made use of various libraries and frameworks to streamline my workflow and enhance the functionality of my website. Overall, my experience working with HTML, CSS, and JavaScript was challenging but rewarding, and I am pleased with the final result.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- JavaScript



### What I learned


```html
<form></form>
```
```css
.proud-of-this-css {input[type=number]::-webkit-inner-spin-button, 
input[type=number]::-webkit-outer-spin-button { 
  -webkit-appearance: none; 
}
}
```
```js
    if (input === monthInp) {
      const monthValue = parseInt(value);
      if (monthValue > 12 || monthValue < 1) {
        monthLabel.style.color = "hsl(0, 100%, 67%)";
        input.style.borderColor = "red";
        parent.querySelector("small").innerText = "Must be a valid month";
        validator = false;
      } else {
        monthLabel.style.color = "black";
      }
    }
```



### Continued development

I'm going to continue on my journey to be a JavaScript genius


## Author

- Frontend Mentor - [@kvngfax](https://www.frontendmentor.io/profile/kvngfax)
- Twitter - [@kvngfax](https://www.twitter.com/kvngfax)    