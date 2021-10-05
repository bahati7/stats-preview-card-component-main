# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

https://github.com/bahati7/stats-preview-card-component-main/blob/main/screenshots/desktop-design.jpg
https://github.com/bahati7/stats-preview-card-component-main/blob/main/screenshots/mobile-design.jpg



### Links

- Solution URL: https://www.frontendmentor.io/solutions/statspreviewcardcomponentmain-using-css-flexbox-0rw-ySQAK
- Live Site URL: https://stats-preview-card7.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this project I Learned the use of  flex-wrap: wrap-reverse; property

 see below:


```css
/*media queries*/
@media(max-width:973px){
    .container .card{
        font-size: 14px;
        display: flex;
        flex-wrap: wrap-reverse;
        width: 25rem;
        height: 68rem;
        background-color:var(--Dark_desaturated_blue);
        margin: 0 auto;
        top: 150px;
        position: relative;
        border-radius: 8px;
        /* box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2),0 6px 20px 0
        rgba(0,0,0,0.19); */
    }
}
```



### Useful resources

https://css-tricks.com/snippets/css/a-guide-to-flexbox/ - This complete guide explains everything about flexbox, focusing on all the different possible properties for the parent element (the flex container) and the child elements (the flex items). It also includes history, demos, patterns, and a browser support chart.



## Author

- Website - https://bahatiphilemon.netlify.app/
- Frontend Mentor - https://www.frontendmentor.io/profile/bahati7
- Twitter - https://twitter.com/PhilemonBahati



## Acknowledgments

Thanks to - Frontend Mentor team - https://www.frontendmentor.io/
