# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to use flexbox in a way that it works with me instead of against me.


```css
body{
    background-color: hsl(212, 45%, 89%);
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
```

I orginially was going to add this to the .container class, but then I remebered that flexbox works on a parent and child sort of relationship. So only the items INSIDE the main card was getting centered instead of the actual card itself. To solve this, I had to use the parent container of my qr code container, which was the body.

### Continued development

In my coming projects, I want to learn more about media querries and responsive websties as a whole. It would also help my future websites become accessible to a wider audience.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/maadeha)

