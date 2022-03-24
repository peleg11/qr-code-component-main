# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Built with](#built-with)
  - [Author](#author)

## Overview

### Screenshot

![](./screenshot.jpg)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

```html
<body>
  <div class="container">
    <div class="component">
      <img src="./images/image-qr-code.png" alt="" />
      <div class="header">
        Improve your front-end skills by building projects
      </div>
      <div class="text">
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </div>
      <div class="attribution">
        Challenge by
        <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
          >Frontend Mentor</a
        >. Coded by
        <a href="https://www.frontendmentor.io/profile/peleg11">Shay Peleg</a>.
      </div>
    </div>
  </div>
</body>
```

```css
* {
  box-sizing: border-box;
  font-family: "Rubik", sans-serif;
}
.container {
  background-color: hsl(212, 45%, 89%);
  width: 1440px;
  height: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.component {
  width: 225px;
  background-color: hsl(0, 0%, 100%);
  display: flex;
  align-items: center;
  flex-direction: column;
  text-align: center;
  gap: 8px;
  border-radius: 5%;
  padding: 12px;
}
img {
  flex: 0 1 auto;
  height: 200px;
  border-radius: 5%;
}
.header {
  font-size: 16px;
  font-weight: bold;
  color: hsl(218, 44%, 22%);
}
.text {
  flex: 0 1 auto;
  font-size: 12px;
  color: hsl(220, 15%, 55%);
}
.attribution {
  font-size: 11px;
  text-align: center;
  flex: 0 1 auto;
  color: hsl(220, 15%, 55%);
  width: 111px;
}
.attribution a {
  color: hsl(228, 45%, 44%);
}
```

## Author

- Frontend Mentor - [@peleg11](https://www.frontendmentor.io/profile/peleg11)
