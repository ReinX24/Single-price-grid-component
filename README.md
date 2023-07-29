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
- [Acknowledgments](#acknowledgments)

## Overview

This repository contains my solution to the Single price grid component challenge on Frontend Mentor

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Screenshots folder](/screenshots)

#### Desktop
![desktop screenshot](https://github.com/ReinX24/Single-price-grid-component/blob/main/screenshots/cardDesktop.png)
#### Mobile
![mobile screenshot](https://github.com/ReinX24/Single-price-grid-component/blob/main/screenshots/cardMobile.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/ReinX24/Single-price-grid-component)
- Live Site URL: [Add live site URL here](https://reinx24.github.io/Single-price-grid-component/)

## My process

I first finished completing the HTML first, after that I went ahead and meticulously finished the CSS for the desktop and mobile version of the website.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned how to set attributes to element if the website is being viewed through a mobile device.
```css
@media all and (max-width: 900px) {

    body {
        height: 120vh;
    }

    .card {
        height: 85%;
        width: 90%;
    }

    .top-box {
        height: 35%;
        padding: 5%;
        font-size: 0.95rem;
    }

    .top-box p {
        margin-top: 5%;
    }

    .bottom-box {
        display: block;
        width: 200%;
        height: 35%;
    }

    .bottom-left-section {
        height: 90%;
    }

    .bottom-left-section h3 {
        line-height: 150%;
        margin-bottom: 5%;
    }

    .bottom-right-section h3 {
        line-height: 150%;
        margin-bottom: 5%;
    }

    .bottom-right-section ul {
        line-height: 180%;
    }
}
```
### Continued development

After this project, I will research more on how to create responsive layouts for mobile devices.

### Useful resources

- [The tutorial that greatly helped me finish the project](https://youtu.be/zJSY8tbf_ys) - This helped me build my foundations for coding in HTML and CSS

## Author

- Frontend Mentor - [@ReinX24](https://www.frontendmentor.io/profile/ReinX24)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

I would like to thank Zach Gollwitzer and the freeCodeCamp Youtube channel, without them I would have never finished this project.
