# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). 

## Table of contents

- [Frontend Mentor - Bento grid solution](#frontend-mentor---bento-grid-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./assets/images/Sc.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Implementing a bento grid layout using CSS Grid was a great exercise in responsive design. I learned how to create complex grid areas that adapt to different screen sizes, ensuring the layout remains visually appealing on mobile, tablet, and desktop.

```css
.main-container {
  display: grid;
  grid-template-areas:
    "seven one one four"
    "seven two three four"
    "eight two three four"
    "eight six five five";
}
```

This project reinforced the importance of planning grid layouts beforehand and using media queries effectively for breakpoints.

### Continued development

I want to continue exploring advanced CSS Grid techniques and perhaps integrate JavaScript for interactive elements in future projects. Additionally, focusing on accessibility best practices to ensure all users can navigate the layouts seamlessly.

## Author

- Frontend Mentor - [@sana-zen](https://www.frontendmentor.io/profile/sana-zen)
- GitHub - [@sana-zen](https://www.github.com/sana-zen)
