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

![](screenshots/desktop-preview.jpg)
![](screenshots/mobile-preview-375px.jpg)

These are the screenshots of the component that i coded.
 



### Links

- Solution URL: https://github.com/Rk44-github/QR-Code-Component
- Live Site URL: https://rk44-github.github.io/QR-Code-Component/

## My process
I started with laying out the html markup first.
I used custom fonts from google fonts.
Then styled it using a saperate CSS file and linked it to the html page.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox



### What I learned
Using a proper HTML layout is very important if you want to style it correctly.
I learned that using flexbox can actually reduces alot of work around centering the components and arranging them in a desired manner.

Here is a code snippet that i used to make it easy to centre the component
```html
 <div class="card">
        
           <img class="qr-img"src="./images/image-qr-code.png" alt="QR Code">
        
        <div class="text">
          <h2>Improve your front-end skills by building projects </h2>
          <p>Scan the QR code to visit the front-end mentor and take your coding skills to the next level</p>
        </div>
      </div> 
```
```css
body{
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 5rem;
    padding-top: 10rem;
}
```

## Author

- Website - [Raj Kumar](https://www.your-site.com)
- Frontend Mentor - [@Rk44-github](https://www.frontendmentor.io/profile/@Rk44-github)


## Acknowledgments

I always refer to w3school and mozilla web-dev for properties.


