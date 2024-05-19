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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.jpg)

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

During this project, I learned to effectively use CSS Flexbox to center elements both vertically and horizontally. I also improved my understanding of semantic HTML5 markup and CSS custom properties. Here are some specific code snippets that I’m proud of:

```html
<section class="qr__card">
  <figure class="qr__card-qr">
    <img src="image-qr-code.png" alt="QR Code to Frontend Mentor">
  </figure>
  <h1>Improve your front-end skills by building projects</h1>
  <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level!</p>
</section>
```

```css
body {
  width: 100%;
  min-height: 100dvh;
  display: flex;
  justify-content: center;
  color: hsl(218, 44%, 22%);
  font-family: 'Outfit', sans-serif;
  font-size: 15px;
  background-color: hsl(212, 45%, 89%);
  text-align: center;
  padding: 1rem;
}

.qr__card {
  max-width: 360px;
  margin: auto;
  padding: 1.5rem;
  border-radius: 1rem;
  background-color: hsl(0, 0%, 100%);
}
```

### Continued development

In future projects, I want to continue focusing on improving my responsive design skills, particularly using CSS Grid. I also aim to deepen my understanding of accessibility best practices to ensure my projects are usable by everyone.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/) - This resource helped me understand the details of Flexbox and CSS properties.
- [CSS-Tricks](https://css-tricks.com/) - This site has comprehensive guides and tips that helped me with practical CSS implementations.

## Author

- Website - [Your Name](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

Thanks to the Frontend Mentor community for their feedback and suggestions, which helped me improve my project. Special thanks to [Example User](https://www.example.com) for their insightful articles and tutorials.