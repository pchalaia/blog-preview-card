# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![./screenshot.jpg](./screenshot.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/blog-preview-card-zIT2cJ42i0]
- Live Site URL: [https://pchalaia.github.io/blog-preview-card/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

In this project, I used an SVG image as the container's background. This choice made it easy to keep the image height fixed, no matter how wide it gets, ensuring the design stays consistent on different screens.

The tricky part was making the font size change based on the screen width without using media queries. That’s when I discovered the clamp() function! With just one line of code, the text size became responsive, adjusting smoothly to different screen sizes.
```css
p {
  font-size: clamp(14px, 4vw, 16px);
}
```

I’m excited to use this simple and powerful technique in future projects.
