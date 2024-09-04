# Make It Real - NAME OF THE PROJECT

This is a solution to the 404-not-found-page project of the Make It Real top fullstack developer program.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- Open the URL in a web browser
- Ajust the dimension of the device and see a responsive page

### Screenshot

![](./screenshot.jpg)

## My process

1. Aprender cómo hacer apps responsive
2. Crear HTML semántico con header, main y footer
3. Crear 2 divs, uno con la imagen y el otro con el texto y el botón
4. Agregar clase de css global incluyendo la tipografía [Space Mono](https://fonts.google.com/specimen/Space+Mono)
5. Agregar clase de css para el footer
6. Agregar clase de css para el botón
7. Centrar para Mobile: 375px
8. Agregar margen superior e inferior a la imagen y centrarla
9. Agregar margen superior al botón
10. Poner el footer en la parte baja de la página
11. Colocar 2 columnas para pantallas más grandes
12. Asegurar responsive hasta Desktop: 1440px

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Make responsive apps using @media

```css
@media (min-width: 800px) {
  main {
    flex-direction: row;
    align-items: center;
  }

  .scarecrow, .message {
    margin-top: 0; 
  }
}
```

### Continued development

I'm not completely comfortable with flex properties

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.

## Author

- Linkedin - [Juan Alva](https://www.linkedin.com/in/juan-luis-alva/)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
