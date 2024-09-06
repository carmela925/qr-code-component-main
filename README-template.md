# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/carmela925/qr-code-component-main.git)
- Live Site URL: [Add live site URL here](https://qr-code-component-main-two-dun.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I have recalled myself on some fundamental notions of html and css like css selectors.

This is the code I added:

```html
  <div class="qr-component">
    <img src="./images/image-qr-code.png" alt="qr-component">
    <h1>Improve your front-end skills by building projects</h1>
    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
```
```css
    *{font-family: "Outfit", sans-serif;}
    body{background-color: hsl(212, 45%, 89%);}
    .qr-component{
      display: block;
      width: 300px;
      height: 490px;
      margin: 5% auto;
      padding: 15px;
      background-color: hsl(0, 0%, 100%);
      border-radius: 15px;
      text-align: center;
    }
    img{
      width: 100%;
      border-radius: 15px;
    }
    h1{
      font-size: 22px;
      font-weight: 700;
      color: hsl(218, 44%, 22%);
      margin: 20px 0;
      padding: 0 20px;
    }
    p{
      font-size: 15px;
      font-weight: 400;
      color: hsl(216, 15%, 48%);
      padding: 0 20px;
    }
```

### Continued development

 I hope to now be able to implement javascript and its frameworks in addition to this

## Author

- Website - [Ntankeu Agnes](https://github.com/carmela925)
- Frontend Mentor - [@carmela925](https://www.frontendmentor.io/profile/carmela925)
