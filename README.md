# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout depending on their device's screen size

### Screenshot
![](./images/card-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- To reverse orders of elements when using flexbox
```css
.columns {
    display: flex; 
    flex-direction: row-reverse;
    flex-wrap: nowrap;
}
```
- Applying a tint to images using ::before pseudo-element
```css
.img-holder::before {
    content: "";
    display: block;
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    background: rgba(170, 92, 219, 0.7);
}
```

### Useful resources 
- [Applying a Tint](https://stackoverflow.com/questions/43938860/how-to-tint-image-with-css/43938944) - This helped me with applying tints on images with pseudo elements, highly recomment that you guys check it out
  
### Author
- Github - [Ronald545](https://github.com/Ronald545)
- Frontend Mentor - [@Ronald545](https://www.frontendmentor.io/profile/Ronald545)