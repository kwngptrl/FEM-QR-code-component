# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![Screenshot 2022-11-15](./Screenshot 2022-11-15.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I didn't realize that this was the first project on Frontendmentor. I did the second one, product-preview-card-component-main, first. But it's almost the same.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In style.css, it is not enough to do a display:grid; place-content: center; Because it still won't center the canvas. One has to include a margin: auto; to finally see the entire canvas centered. This, I verified from a tutorial from a YouTuber named Dave Gray in his React tutorial, whose CSS code I examined.

```css
.container {
    display: grid;
    place-content: center;
    /* more code here */
    margin: auto;
}
```

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)