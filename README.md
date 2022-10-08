# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](Screenshot.png)

### Links

- Solution URL: [Github](https://github.com/CHEN-YiWen/Single-price-grid-component)
- Live Site URL: [live site hosted by Github](https://chen-yiwen.github.io/Single-price-grid-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow


### What I learned

- I try out the simplest way to use <code>display: grid</code>. This challenge is perfect for me who just started really learning it since it is not tricky.

- If I need to set <code>border-radius</code> to <code>main</code>, I also nedd to set up <code>overflow: hidden</code> to stop the childs from overflowing... or there will be extra little white space outside the corner of the <code>main</code>.
```css
main{
    width: min(650px, 80%);
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    border-radius: 0.65rem;
    overflow: hidden;
}
```

- I also use <code>clamp()</code> for the font-size. I think it's a useful tool to make the layout more responsive and pretty.


### Continued development

- I guess my html is not semantic enough. I will try to improve it later.

- I will also go through my css code again so that I can make it simpler.

### Useful resources

- [Box Shadow CSS Generator
](https://cssgenerator.org/box-shadow-css-generator.html) - I use it to generator box shadow. It helps to reduce great amount of time to create nice results.

## Author

[@CHEN-YiWen](https://www.frontendmentor.io/profile/CHEN-YiWen)


