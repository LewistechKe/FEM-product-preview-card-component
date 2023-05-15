# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](.images/screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

```html
<div class="container">
      <div class="card">
        <div class="card-img"></div>
        <div class="card-info">
          <p class="sub-title">PERFUME</p>
  
        <h1 class="title">Gabrielle <br> Essence Eau <br> De Parfum</h1>
        <p class="info">
          floral, solar and voluptuous interpretation composed by Olivier Polge,
          Perfumer-Creator for the House of CHANEL.
        </p>
        <div class="prices">
          <h2>$149.99</h2>
          <p>$169.99</p>
        </div>
  
        <button>
          <img src="./images/icon-cart.svg" alt="cart" />Add to Cart
        </button>
        </div>
      </div>
    </div>
```
```css
@media screen and (max-width:550px) {
    .container{
        width: 350px;
    }
    .card{
        flex-direction: column;
        align-items: center;
    }
    .card-img{
        background-image: url('./images/image-product-mobile.jpg');
        background-size: cover;
        border-radius: .5rem .5rem 0 0;
        height: 250px;
        width: 100%;
        background-repeat: no-repeat;
    }
    .card-info{
        width: 100%;
    }
}

```

## Author

- Website - [www.lewistech.co.ke](https://www.lewistech.co.ke)
- Frontend Mentor - [Digibloc](https://www.frontendmentor.io/profile/Digibloc)
- Twitter - [Lewistech ke](https://www.twitter.com/lewistech)


