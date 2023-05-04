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

## Overview

### Screenshot

![](https://d-g-szabo.github.io/qr-code-component-main/design/solution-design.jpg)

### Links

- Solution URL: [Solution URL here](https://d-g-szabo.github.io/qr-code-component-main/)
- Live Site URL: [Live site URL here](https://d-g-szabo.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

Adding the custom fonts to this project was very interesting. Had to make new files for the fonts with the linked website below. Also this code added the fonts to the website to be able to use it:
```css
@font-face {
    font-family: 'outfitbold';
    src: url('font/outfit-bold-webfont.woff2') format('woff2'),
         url('font/outfit-bold-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
```

Adding Phone resolution to the website was not too hard thanks to this easy solution which workls like an if statement:
```css
@media only screen and (max-width: 600px) {
    body {width: 375px; height: 200px;}
  }
```

Setting up the Main div was the hardest part to make the website look like the design one, I am happy with the solution and that I finnaly learned how to make shadows to boxes and make the box corners round. Did not think so that it was this easy tho:
```css
.main {
    background-color:#ffffff;
    text-align: center;
    padding: 15px;
    width:min-content;
    margin: auto;
    border-radius: 16px;
    margin-top: 200px;
    box-shadow: 1px 2px 20px #8888;
}
```

### Continued development

I still need to focus on learning to develop sites with in mind of different resolutons as we seen at the phone res part.

Also a structure which I should use to make websites could make the planning much more easy.

### Useful resources

- [Webfont Generator](https://www.fontsquirrel.com/tools/webfont-generator) - This helped me for make the custom font for this project.
- [Custom fonts for website](https://www.pagecloud.com/blog/how-to-add-custom-fonts-to-any-website) - This is an amazing article which helped me finally understand how to add custom fonts to my website. I'd recommend it to anyone still learning this concept.
- [w3schools](https://www.w3schools.com/css/default.asp) - Used this amazing website to remind me of important syntax. 
- [Images sizing](https://www.smashingmagazine.com/2020/03/setting-height-width-images-important-again/) - This is an amazing article which helped me finally understand why is it important to set height and width on images.


## Author

- GitHub Profile - [Daniel G Szabo](https://github.com/d-g-Szabo)
- Frontend Mentor - [@d-g-Szabo](https://www.frontendmentor.io/profile/d-g-Szabo)
