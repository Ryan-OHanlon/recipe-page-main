# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![screenshot](./screenshot.jpeg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/recipe-page-using-flexbox-and-media-css-rule-vPirkXX_IP](https://www.frontendmentor.io/solutions/recipe-page-using-flexbox-and-media-css-rule-vPirkXX_IP)
- Live Site URL: [https://ryan-ohanlon.github.io/recipe-page-main/](https://ryan-ohanlon.github.io/recipe-page-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This challenge taught me a lot about the @media CSS rule for creating a responsive design for both desktop and mobile. Being able to have two sets of CSS rules based on the width of the device makes designing webpages a challenge as the mobile CSS rules can still affect the @media CSS rules.

```css
/*Desktop CSS rules when wider than 375px*/
@media (min-width: 376px) {
    body{
        display: flex;
        flex-direction: column;    
        background-color: hsl(30, 54%, 90%);
        padding: 25%;
    }

    main{
        background-color: hsl(0, 0%, 100%);
        border-radius: 1em;    
        padding: 2em;
    }

    img{
        width: 100%;
        height: auto;
        border-radius: 1em;
    }
    div.margin{
        margin: 0px;
    }
}
```
The other thing I learned was using the ::marker pseudo class to change the font weight of the ol element so each number appears bold and to color the bullet points in the ul elements. There were a lot of small formatting and css rules I had to learn to match the design.

```css
ul.preplist > li::marker{
    color: hsl(332, 51%, 32%);
}

ol > li::marker{
    font-weight: 700;
}
```

### Continued development

I'd like to develop a better understanding of how to structure CSS rules using the @media only rule. Having to create two sets of CSS rules for both mobile and desktop without a framework is a challenge.

Having to design a webpage for two different devices makes designing the HTML framework a greater challenge so you can have the CSS rules work for both desktop and mobile.

The other skill I'd like to keep learning is responsive web design. I don't know what the appropriate width I should be using in order to match the desktop-design.jpg.

### Useful resources

- [W3schools](https://www.w3schools.com/css/default.asp) - This helped me with learning the @media CSS rule, the property for creating a bottom border when using table elements, text-indent, and the ::marker pseudo class to change the font weight of ordered lists and color of unordered lists.

## Author

- Website - [Ryan O'Hanlon](https://ryan-ohanlon.github.io/)
- Frontend Mentor - [@Ryan-OHanlon](https://www.frontendmentor.io/profile/Ryan-OHanlon)
- Twitter - [@RyanROhanlon](https://x.com/RyanROHanlon)

## Acknowledgments
