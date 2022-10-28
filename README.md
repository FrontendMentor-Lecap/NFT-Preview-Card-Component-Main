# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/images/screenshot.jpg)

### Links

- Solution URL: [https://github.com/FrontendMentor-Lecap/NFT-Preview-Card-Component-Main]
- Live Site URL: [https://frontendmentor-lecap.github.io/NFT-Preview-Card-Component-Main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this project I learned about `display: flex` and image positioning in the background of a `<DIV>` and also as a `:hover` state. It was really important to understand how the background image works and how to position it. In this specific case I used the main image as the background with a background size of cover:

```css
.image {
    height: 280px;
    border-radius: 5px;
    background-image: url("./images/image-equilibrium.jpg");
    background-size: cover;
```

And when hovering the `<div>` the image appears with the display:

```css
.image img {
  display: none;
  padding: 200px;
  background-color: hsla(178, 100%, 50%, 0.7);
}

.image:hover {
  cursor: pointer;
}

.image:hover > img {
  display: block;
}
```

### Continued development

I have to continue developing in CSS Grid and responsiveness. Also improving HTML semantics to have better accessibility and SEO results.
