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
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop](/images/desktop-screenshot.png)    
![Mobile](/images/mobile-screenshot.png)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/nft-preview-card-_qTHt6MWzS)
- [Live Site URL](https://coyag.github.io/3-nft-preview-card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Google Fonts

### What I learned

How to do an overlay! The code:
```css
.overlay{
  width: 100%;
  height: 100%;
  display: flex;
  visibility: hidden;
  justify-content: center;
  align-items: center;
  background-color: hsla(178, 100%, 50%, 0.5);
}
.overlay>img{
  width: 40px;
  height: 40px;
}
.main-cube:hover .overlay{
  visibility: visible;
}
```

### Continued development

I would like to continue building my web development skills.

## Author

- Website - [GitHub](https://github.com/CoyaG)
- Frontend Mentor - [@CoyaG](https://www.frontendmentor.io/profile/CoyaG)
- Twitter - [@CoyaG1](https://twitter.com/CoyaG1)

## Acknowledgments

Shoutout to [Melvin Aguilar](https://www.frontendmentor.io/profile/MelvinAguilar) who helped me realize the other picture was an overlay.