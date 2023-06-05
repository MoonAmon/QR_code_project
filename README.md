# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](images/Screenshot.png)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

Understanding the functioning of the CSS box model (padding, margin, border...) and the appropriate use of pseudo tags in HTML.


```html
<div class="qr_card">
    <img src="images/image-qr-code.png" alt="">
    <div class="qr_text">
      <h2>Improve your front-end skills by building projects</h2>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </div>
```
```css
qr_card {
    width: 350px;
    height: 490px;
    background-color: hsl(0, 0%, 100%);
    padding: 30px;
    border: 1px solid #ccc;
    border-radius: 20px;
    margin: 100px 500px 100px 500px;

}

.qr_text{
    font-family: Outfit, sans-serif;
    text-align: center;   
}
```
## Author

- Frontend Mentor - [@MoonAmon](https://www.frontendmentor.io/profile/MoonAmon)

