# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
@media only screen and (max-width: 768px) {
    .card {
        display: flex;
        flex-direction: column;
        max-width: 343px;
        max-height: 611px;
    }
    
    .card-image {
        width: 50%;
    }

    .product-image-desktop {
        display: none;
    }

    .product-image-mobile {
        display: flex;
        width: 343px;
        height: 240px;
        border-radius: 10px 10px 0 0;
    }

    .description-box {
        background-color: white;
        width: 295px;
        height: 371px;
        padding: 20px 24px;
        border-radius: 0px 0px 10px 10px;
    }

    .product-name {
        width: 295px ;
        margin-top: 8px;
        margin-bottom: 16px;
    }

    .product-description {
        width: 295px;
    }

    .price {
        margin: 24px 0px 20px 0px
    }

    button {
        width: 295px;
        height: 48px; 
        justify-content: center;
    }
}
```

### Useful resources

- [How to Make a Website Responsive | Learn HTML and CSS | Full Course For Beginners](https://www.youtube.com/watch?v=ZYV6dYtz4HA)

## Author

- Frontend Mentor - [@isaiahp04](https://www.frontendmentor.io/profile/isaiahp04)

