# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./ScreenShot_Desktop.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

The major leasons I took away from this how to use css variables to aid in responsive design. 
I also learn of clamp() function in css that helped me created variable fonts.

Additional I learned how to create a responsive nav bar and use js to toggle classes.

```css
:root {
  --ff-size-heading-xl: clamp(1rem, 2vw + 0.1rem, 4rem);
  --ff-size-heading-sm: clamp(1rem, 1.5vw + 0.1rem, 3rem);
  --ff-size-body: clamp(0.7rem, 1vw + 0.1rem, 2rem);
}

```
### Continued development

I will continue to refactor and optimize the code as I continue to learn more.

### Useful resources

- [Simple solutions to responsive typography](https://www.youtube.com/watch?v=wARbgs5Fmuw) - This helped me with responsive typography. I really liked these methods and will use it going forward.

- [Responsive Layouts](https://www.youtube.com/watch?v=7khSaA91e04&list=PL4-IK0AVhVjM6kuUoUexfmnD8vHtZkXdd) - This is an amazing video playlist which helped me finally understand and implement responsive layouts. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@Mondara](https://www.frontendmentor.io/profile/Mondara)
- Linkedin - [@Mondara](https://www.linkedin.com/in/mondara-thotage/)
