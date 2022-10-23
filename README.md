# Frontend Mentor - NFT preview card component

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
    - [Links](#links)
      - [My process](#my-process)
        - [Built with](#built-with)
        - [What I learned](#what-i-learned)
      - [Author](#author)

## Overview

### Screenshot

![](./images/Screenshot%202022-10-23%20110843.png)

### Links

- GitHub Repo: [](https://github.com/MostafaHamdy3/NFT-Preview-Card)
- Live Demo: [](https://nft-preview-card-five-tau.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

- Position of images
- Opacity & Transition

```css
.img::after {
  background: var(--primary-cyan);
  content: url(images/icon-view.svg);
  position: absolute;
  inset: 0;
  opacity: 0;
  transition: all 0.25s ease;
}

.img:hover::after {
  opacity: 0.5;
}
```

## Author

- Portfolio - [](https://mostafa-portfolio.vercel.app/)
- Frontend Mentor - [@MostafaHamdy3](https://www.frontendmentor.io/profile/MostafaHamdy3)
