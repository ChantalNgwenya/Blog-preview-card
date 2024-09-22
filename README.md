# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges helps me improve my coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

<img src="./Screenshot .png" width="800" />


### Links

- Solution URL: [Chantal Ngwenya]([https://github.com/ChantalNgwenya](https://github.com/ChantalNgwenya/Blog-preview-card))
- Live Site URL: [Chantal's live site](https://blog-preview-card-kappa-seven.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles


### What I Learned

1. **Responsive Design**: I implemented a responsive layout for the blog preview card using Flexbox. This allows the card to adapt to different screen sizes smoothly.

   ```css
   @media screen and (min-width: 200px) and (max-width: 1000px) {
       .main-container {
           width: 80%;
       }
   }
   ```

2. **Smooth Scroll Behavior**: I set a smooth scroll behavior for the entire document, enhancing user experience when navigating the page.

   ```css
   html {
       scroll-behavior: smooth;
   }
   ```

3. **Hover Effects**: I utilized hover effects to create a more interactive experience. The main container changes its box shadow on hover, and the title changes color, indicating that they are clickable elements.

   ```css
   .main-container:hover {
       box-shadow: 15px 15px 0px 0px;
   }
   
   .body-content h1:hover {
       color: hsl(47, 88%, 63%);
       cursor: pointer;
   }
   ```

4. **Custom Fonts**: I integrated a Google Font (`Figtree`) to enhance the typography of the card, making it more visually appealing.

   ```css
   @import url('https://fonts.googleapis.com/css2?family=Figtree:wght@300..900&display=swap');
   ```

5. **CSS Variables and Custom Properties**: Although not directly shown in my code, learning about CSS variables can help manage colors and other properties more efficiently in future projects.

### Continued development

I am going to ponder on anything that might be helpful.

To also play arond css properties.

### Useful resources

- [Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics) - This is an amazing article which helped me understand HTML basics.


## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yChantalNgwenya)
- Live Site URL: [Chantal's live site](https://blog-preview-card-kappa-seven.vercel.app/)


## Acknowledgments

I got help on how to approach the project from YouTube and [Mozilla documentation](https://developer.mozilla.org).

