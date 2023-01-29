# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [MY SOLUTION:](#my-solution)
    - [My Unsure solutions](#my-unsure-solutions)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)


## Overview

### Screenshot

![](final.png)

I didn't know that it would take hours for me to finish it. Before I start this challenge, I thought this challenge was easy as I have knowledge about CSS and recently relearn it. But you'll never know what learned if you didn't apply it. So, thanks for this challenge I learned a lot about display, positioning and alignments. Although I didn't apply the mobile as I don't about it yet, so, I din't know if it's responsive to mobile app. But in desktop browsers it's responsive.


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Box-shadow
- Display
- Flexbox

### What I learned

It was very difficult for me to decide what properties I should used in every tag especially in div tag and I know that the properties I used are somewhat wrong.

I am confused about div at the beginning and how I can centralize it.

So, at this challenge I was able to learn a liitle bit about the display properties, alignment, flexbox and linking an external font. 

### MY SOLUTION:

```html
<div class="container">
    <img src="images/image-qr-code.png" alt="QR-code">
    <p class="title">Improve your front-end skills by building projects</p>
    <p class="description">Scan the QR code to visit Frontend Mentor and take you coding skills to the next level</p>
</div>
<p class="source">Challenge by <a href="https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H" alt="Frontend Mentor"> Frontend Mentor</a>. Coded by Patricia Ann C. Mahinay</p>
```
***CSS for body and div***
```css
@font-face {
    font-family: Outfit;
    src: url(https://fonts.google.com/specimen/Outfit);
}

body{
    background-color: hsl(212, 45%, 89%);
    font-family: 'Outfit', sans-serif;
    padding-top: 3%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

div.container{
    margin: 0px;
    padding: 15px;
    border-radius: 20px;
    background-color: white;
    width: 330px;
    text-align: center;
    box-shadow: 5px 5px 10px rgb(200, 193, 193) ;
}
```
***CSS for images and texts***
```css
img{
    width: 100%;
    height: auto;
    border-radius: inherit;
}


p.title{
    color: hsl(218, 44%, 22%);
    font-weight: 700;
    font-size: 24px;
}

p.description{
    color: hsl(220, 15%, 55%);
    font-weight: 400;
    padding: 0px 10px;
    font-size: 18px;
}

p.source{
    display: block;
    text-align: center;
}

a{
    text-decoration: none;
    font-weight: bold;
}
```

### My Unsure solutions

1. The padding at the top. Since I cannot center my div, I added a padding at the top od the body element. Also, I am not sure if the display, flex-direction, and justify-content properties should be in the body element.
   ```css
     body{
       padding-top: 3%;
       display: flex;
       flex-direction: column;
       justify-content: center;
   }
   ```
2. Feel free to comment if there are code that needs to be fixed and change.

### Continued development

As I am still confused and uncomfortable using div tag, display, alignment, flexbox, box-shadow properties I will continue to focus on it. 

### Useful resources

- [Flexboxfroggy](https://flexboxfroggy.com/) - This helped me know how justify-content, flex-direction, and aligning items works vissully.

## Author

- Frontend Mentor - [@ptrcmahinay](https://www.frontendmentor.io/profile/ptrcmahinay)