# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I learned how to do cards using div, classes and styles. That's great I can use it in the future.


```html
  <div class="container">
    <div class="c-card">
      <img src="/images/image-qr-code.png" alt="Qr-code">
   
      <h2>Improve your front-end skills by building projects</h2>

      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p> 
    </div>
```
```css
.container {
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.c-card {  
    text-align: center;
    width: 200px;
    height: 350px;
    background-color: #fff;
    border-radius: 16px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    margin-bottom: 20px;
}
```


### Continued development

I will continue improving on styles, I feel that I still have some difficuties with that.

### Useful resources

- [StackOverflow](https://pt.stackoverflow.com/questions/551133/centralizar-texto-com-card) - This is an amazing article which helped me finally understand how to do a card. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@rodrspdev](frontendmentor.io/profile/rodrspdev)
- Github - [@rodrspdev](https://github.com/rodrspdev)
