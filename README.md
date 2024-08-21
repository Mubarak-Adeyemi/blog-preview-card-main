
# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot 1](/blog-preview-card-main/assets/Screenshot_20240820_221226_Spck Editor.jpg)
![Screenshot 2](/blog-preview-card-main/assets/Screenshot_20240820_221343_Spck Editor.jpg)
![Screenshot 3](/blog-preview-card-main/assets/Screenshot_20240820_221359_Spck Editor.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/Mubarak-Adeyemi/blog-preview-card-main)
- Live Site URL: [Add live site URL here](https://mubarak-adeyemi.github.io/blog-preview-card-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

During this project, I focused on creating a responsive card component using HTML and CSS. I refined my understanding of Flexbox for layout management and practiced the use of custom properties in CSS to maintain consistent styling across the project. Here's a snippet that showcases the card container's styling:

```css
.card-container{
  width: 300px;
  background-color: #ffffff;
  display: flex;
  flex-direction: column;
  justify-content: center;
  border-radius: 15px; 
  padding: 20px;
  border:2px solid #000 ;
  box-shadow: 0px 0px 9px 0px rgba(66, 68, 90, 1); 
}

.card-container:hover{
  border: 2px solid #000;
  box-shadow: 6px 6px 0px 0px rgb(0, 0, 0);
}
```

### Continued development

Moving forward, I plan to deepen my understanding of responsive design by incorporating CSS Grid in more complex layouts. Additionally, I'd like to explore CSS animations to enhance user interaction and experience.

### Useful resources

- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This resource helped me better understand Flexbox and how to use it effectively in layouts.
- [MDN Web Docs - CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/--*) - This guide was essential for understanding and implementing CSS custom properties.

## Author

- Frontend Mentor - [@MubarakAdeyemi](https://www.frontendmentor.io/profile/MubarakAdeyemi)

## Acknowledgments

I would like to thank Frontend Mentor for providing this challenge, which was a great opportunity to practice and improve my HTML and CSS skills.