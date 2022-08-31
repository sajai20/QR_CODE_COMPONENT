# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help us to improve our coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)


## Overview
In this project i have given the solution for QR code components from Frontend Mentor
### Screenshot

![](./screenshots/Capture.PNG)


### Links

- Solution URL: [solution URL here](https://github.com/sajai20/QR_CODE_COMPONENT/)
- Live Site URL: [live site URL here](https://eclectic-gecko-795685.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

In this project i have learnt how box model works and how to display flex property

```html
<body>
  <div class="container">
    <div class="row">
      <div class="card">
        <div class="card_img_container">
          <img src="./images/image-qr-code.png" alt="qr_code_image">
        </div>
        <div class="card_content_container">
          <h1 class="card_title">Improve your front-end skills by building projects</h1>
          <p class="card_description">Scan the QR code to visit Frontend Mentor and take your coding skills to the next
            level</p>
        </div>
      </div>
    </div>
  </div>
```
```css

@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --clr-White: #ffffff;
    --clr-Light-gray: #d6e2f0;
    --clr-Grayish-blue: #7b879d;
    --clr-Dark-blue: #1f3251;
}

/* only for paragraph */
html {
    font-size: 15px;
}

body {
    font-family: 'Outfit', sans-serif;
    background-color: var(--clr-Light-gray);
}

.container {
    width: 100%;
    /* margin: auto; */

}

.row {
    display: flex;
    flex-wrap: wrap;
    height: 750px;
    justify-content: center;
    align-items: center;
}

img {
    width: 100%;
    height: auto;
}

.card {
    background-color: var(--clr-White);
    padding: 1.25rem;
    width: 323px;
    /* margin: auto; */
    border-radius: 10px;
}

.card_img_container {
    margin-bottom: 1.5rem;
}

/* if we want to give the border radius for the image we need to add radius by mentioning the ing tag using parent class */
.card_img_container img {
    border-radius: 10px;
}

.card_content_container {
    text-align: center;
    margin-left: 1.25rem;
    margin-right: 1.25rem;
}

.card_title {
    font-size: 20px;
    font-weight: 700;
    color: var(--clr-Dark-blue);
    margin-bottom: 1.5rem;
}

.card_description {
    font-weight: 400;
    color: var(--clr-Grayish-blue);
    margin-bottom: 2rem;
}
```




## Author

- Website - [sajaikumar](https://eclectic-gecko-795685.netlify.app/)
- Frontend Mentor - [@sajai20](https://www.frontendmentor.io/profile/yourusername)
