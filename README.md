# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](Design,making responsive)
  - [HTML5,CSS]
  - [media queries, placement of div]
  - [MDN , Stackoverflow, web3Schools]
  - [media query , flexbox]
- [Mridul garg]



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
image.png

### Links

- Solution URL: [Add solution URL here]
- Live Site URL: [Add live site URL here]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

In this project i came across various problems. some the major are media queries , effective use of flex box , div alingment.


```html
  <main>

    <div class="Sedans card">
      <img src="images/icon-sedans.svg" alt="Sedans" />
      <h1>SEDANS</h1>
      <p>Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city
        or on your next road trip.</p>
      <button type="button" name="button">Learn More</button>
    </div>
    ...</main>
```
```css
@media (max-width:842px) {
  body{
    display: flex;
    width: 100%;
    overflow: scroll;
  }
  main{
    flex-direction: column;
    flex-wrap: nowrap;
    height: auto;
    margin-top: 20px;
  }
  ....
}

```

### Continued development

- Media queries
- Positioning

### Useful resources

- [https://css-tricks.com/snippets/css/a-guide-to-flexbox/] - This helped me for understanding flexbox. I really liked this pattern and will use it going forward.
- [https://youtu.be/e2zzDcyI_nA] - This is an amazing video on youtube which helped me finally understand nedia queries. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Mridul Garg](https://www.your-site.com)
- Frontend Mentor - [@Mridul07garg](https://www.frontendmentor.io/profile/Mridul07garg)
- Twitter - [@MridulG27253526](https://www.twitter.com/MridulG27253526)


