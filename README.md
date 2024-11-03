# Frontend Mentor - Social Links Profile Solution

This is a solution to the [Social Links Profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page.
- Navigate through the links using only the keyboard, with visual focus indicators.

### Screenshot

!Desktop View[Screenshot of the solution](./assets/images/desktop-view.png)
!Mobile View[Screenshot of the solution](./assets/images/mobile-view.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

This project helped reinforce the importance of **semantic HTML** and **keyboard accessibility** for a better user experience. By using proper HTML elements such as `<main>`, `<header>`, and `<nav>`, I improved the structure and accessibility of the profile card.

Additionally, I learned more about creating **focus styles** for interactive elements to ensure that keyboard users can easily navigate the links. Here’s a code snippet that demonstrates how I handled focus states:

```css
.avatar-profiles a:hover,
.avatar-profiles a:focus {
  background-color: var(--green);
  color: var(--grey-800);
}
```

### Continued development

For future projects, I want to:

- Continue practicing accessible design by improving ARIA usage and keyboard navigation.
- Explore more advanced CSS techniques for animations and transitions to enhance interactivity.

### Useful resources

- [MDN Web Docs - Accessible HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) - This provided a good reference for choosing semantic elements.
- [The Markdown Guide](https://www.markdownguide.org/) - This was useful for writing better documentation and learning about Markdown formatting.

## Author

- Website - [Mayen](https://github.com/Mayen007)
- Frontend Mentor - [@Mayen007](https://www.frontendmentor.io/profile/Mayen007)

## Acknowledgments

Thanks to Frontend Mentor for providing this challenge. It helped me practice accessible design and improve my coding skills through a hands-on project.
