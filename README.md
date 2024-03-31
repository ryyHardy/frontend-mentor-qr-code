# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

![](./solution-screenshot.png)

### Links

- Solution URL: [https://github.com/ryyHardy/frontend-mentor-qr-code](https://github.com/ryyHardy/frontend-mentor-qr-code)
- Live Site URL: [https://ryyhardy.github.io/frontend-mentor-qr-code/](https://ryyhardy.github.io/frontend-mentor-qr-code/)

## My process

### Built with

- Semantic HTML
- CSS

### What I learned

In the HTML, I realized that a figure element would be a good choice. It allows for both an image and text, which is perfect for this component.
I can see myself using figures a lot in the future. It allowed me to simplify it down to some very readable HTML. I also learned that you don't
need Flexbox for everything.

```html
<figure class="qr-card">
  <img src="images/image-qr-code.png" alt="QR Code" />
  <figcaption>
    <p class="qr-title">
      Improve your front-end skills by building projects
    </p>
    <p class="qr-desc">
      Scan the QR code to visit Frontend Mentor and take your coding
      skills to the next level
    </p>
  </figcaption>
</figure>
```
