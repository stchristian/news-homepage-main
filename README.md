# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- [Solution url](https://github.com/stchristian/news-homepage-main)
- [Live site url](https://stchristian.github.io/news-homepage-main/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS and BEM
- Flexbox & CSS Grid
- Mobile-first workflow

### What I learned

I learned how to change the image depending on the media properties using `<picture>` element. This problem is also called [**art direction**](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images#art_direction)

```html
<picture class="featured-article__img">
  <source srcset="./assets/images/image-web-3-desktop.jpg" media="(min-width: 400px)" />
  <img src="./assets/images/image-web-3-mobile.jpg" />
</picture>
```

I learned how to write a more accessible hamburger menu using `aria` attributes. Keyevent are not supported though.

In the _scss_ files I tried to rely on the following structure when writing styles:

1. first come the mixins
2. styles
3. pseudo class selectors
4. responsive mixin
5. any sub element styles using the same structure

### Continued development

I should probably verify the good usage of semantics on the page.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/stchristian)
