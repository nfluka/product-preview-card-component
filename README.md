# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM


### What I learned

At first I ditn't know how to add responsive images to the HTML, and I didn't want to do images in CSS as backgrounds. So I explored [responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) on MDN, and [CSS-tricks](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/#using-srcset). I decided to use srcset in the end.

Below is code on how I did it in end:

```html
<img 
  srcset="/images/image-product-desktop.jpg"
  src ="/images/image-product-mobile.jpg" 
  alt="Perfume"
  sizes="(max-width: 425px)"
>
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development

I would like to focsu more on learning BEM and incorporating this in my future solutions. In next chalanges id like to try out [SASS](https://sass-lang.com/) to help me learn how to organize my CSS better, and with time, as i progress in my studies, refactor all this solutions using ract.

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - This is always great resoruce for whenever I get stuck.
- [CSS-TRICKS](https://css-tricks.com/) - When Im stuck on something with CSS I always find good atricles and explanations here.
- [Kevin Powel](https://www.youtube.com/kevinpowell) - Awesome guy, go check his youtube. Great tacher and content if you starting your frontend development journey.

## Author

- Nenad Fluka - [@nfluka](https://www.frontendmentor.io/profile/nfluka)

