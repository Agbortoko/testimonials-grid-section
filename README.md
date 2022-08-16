# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Challenge URL](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7)
- Live Site URL: [live Preview of Solution](https://agbortoko.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned how to work with css grid! It's quite fun. I also sharpened my use of the mobile first workflow.

```css
@media screen and (min-width: 780px) {

    .testimonial{
        max-width: 1440px;
        margin: 100px auto;
        grid-template-columns: repeat(4, 1fr);
    }
    
    .card:nth-of-type(1){
        grid-column: 1 / 3;
    }

    .card:nth-of-type(3){
        grid-column: 4;
        grid-row: 1 / 3;
    }

    .card:nth-of-type(5){
        grid-column: 2 / 4;
    }

}


```

Apart from the grid i learned some new css tricks i had no idea of before like the background positioning with values

```css

.card--bg-voilet{
    background: var(--voilet);
    color: var(--white);
    background-image: url('./images/bg-pattern-quotation.svg');
    background-repeat: no-repeat;
    background-position: top 10px right 100px;
}

```



### Useful resources

- [CSS Grid Layout Module](https://www.w3schools.com/css/css_grid.asp) - This helped me understand a litle bit more about CSS grid

## Author

- Website - [Easythingz](https://easythingz.net)
- Frontend Mentor - [@agbortoko](https://www.frontendmentor.io/profile/agbortoko)
- Twitter - [@agbortoko_arrey](https://www.twitter.com/agbortoko_arrey)


