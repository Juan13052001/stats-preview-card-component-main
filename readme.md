# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

### Screenshot
Desktop

![](screenshot-Desktop.jpeg)
Mobile

![](screenshot-mobile.jpeg)

### Links

- Solution URL: [GitHub repository](https://github.com/Juan13052001/stats-preview-card-component-main)
- Live Site URL: [My Site](https://juan13052001.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned the basics of CSS grid, how to arrange and how to apply it when using media queries.

```css
@media(max-width:375px) {
    body {
        display: block;
        text-align: center;
    }

    .container {
        border-radius: 25px;
        margin: 0;
        width: 350px;
        height: 650px;
        grid-template-rows: repeat(3, 1fr);
    }

    .image {
        grid-column: 1/6;
        order: -1;
    }

    .image-desktop {
        width: 350px;
        height: 250px;
        object-fit: cover;
    }

    .fondo {
        grid-column: 1/6;
        height: 250px;
        order: -1;
    }

    .text {
        grid-column: 1/6;
        grid-row: 2;
        order: 1;
    }

    .title {
        text-align: center;
        font-size: 20px;
        width: 275px;
        padding: 0;
        padding-left: 30px;
    }

    .content {
        text-align: center;
        width: 225px;
        padding: 0;
        padding-left: 30px;
    }

    .datos-numeros {
        width: 250px;
        text-align: center;
        grid-template-columns: 1fr;
        grid-template-rows: repeat(3, 1fr);
        padding: 0;
        padding-left: 30px;
        margin: 0;
    }
}
```

### Continued development

I want to continue learning how to use and apply CSS grid for layout and how to arrange my HTML elements.

## Author


- Frontend Mentor - [@Juan13052001](https://www.frontendmentor.io/profile/Juan13052001)