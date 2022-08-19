# Frontend Mentor - NFT preview card component solution

![Web design layout of front end mentor QR Code Component Solution](./design/desktop-design.jpg)
![Web page design with drawn out box containers](./design/Container%20Outline.jpg)

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/).

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process and what I learned](#my-process-and-what-i-learned)
  - [Built with](#built-with)
  - [Continued development and resources](#continued-development-and-resources)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### Links

- XD Prototype: [https://xd.adobe.com/view/bfae9302-4307-46c2-8b5e-30d5c7f8b815-eafd/](https://xd.adobe.com/view/bfae9302-4307-46c2-8b5e-30d5c7f8b815-eafd/)
- Solution URL: []()
- Live Site URL: [https://codedavidc.github.io/four-card-feature-section-master/](https://codedavidc.github.io/four-card-feature-section-master/)


## My process and what I learned

I created an XD File before coding to create a prototype of the design. I also drew the containers for each element on the page to provide a visualization of how everything is structured before I code.

I learned how to use CSS Grid and positioning imges to the right in a container using CSS Flexbox, and also how to use box-shadow. 


### Built with

- HTML and CSS
- Some BEM CSS class naming convention
- CSS Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned how to use these lines of code:

```html

```
```css
    .card-container {
        margin-left: 30px;
        margin-right: 30px;
        max-width: 1110px;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: repeat(4, 1fr);
        grid-template-areas: 
        ". two ."
        "one two four"
        "one three four"
        ". three .";
        gap: 30px;
    }

    .card--one {
    border-top: 4px solid var(--cyan);
    grid-area: one;
    }
    
    .image {
    width: 100%;
    padding-top: 32px;
    display: flex;
    justify-content: end;
    }

    .card {
    background-color: var(--card);
    border-radius: 7px;
    padding: 23px 27px 27px;
    max-width: 310px;
    margin-top: 25px;
    box-shadow: 7px 7px 14px hsla(216, 92%, 75%, .2);
    }

```


### Continued development and resources

In the future, I want to be able to work faster and create nav bars with fluidly using flexbow. 

- [CSS Tricks: A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me with CSS Grid.
- [MDN Web Docs: Box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - This helped me with styling box shadows.
- [CSS Tricks: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me with CSS Flexbox positioning. 


## Author

I'm a Creative Professional working with Motion, Web, and Graphic Design. 
Learn more about my me and my work below! 😀

- Website - [designsdavidc.com](https://www.designsdavidc.com)
- LinkedIn - [davidChavezDesign](https://www.linkedin.com/in/davidchavezdesign/)
- Frontend Mentor - [@codeDavidC](https://www.frontendmentor.io/profile/codeDavidC)
- Instagram - [@designsDavidC](https://www.instagram.com/designsdavidc/)
- Behance - [davidchavez2020](https://www.behance.net/davidchavez2020)
