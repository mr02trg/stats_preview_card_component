# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Design](#design)
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

- View the optimal layout depending on their device's screen size

### Design

<img src="design/desktop-design.jpg" alt="drawing" width="800"/>

![](./design/mobile-design.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

- Image Overlay
```css
.stats__image {
  grid-column: 7/13;
  width: 100%;
  min-height: 30vh;
  background-color: hsl(277, 64%, 61%);
  background-image: url('images/image-header-desktop.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  background-blend-mode: multiply;
  border-radius: 0px 10px 10px 0;
}
```

- Responsive design with media query
```css
@media screen and (max-width: 765px) {
  .stats__card {
    grid-template-columns: 1fr;
    grid-template-rows: 240px auto;
    width: 100%;
    background-color: hsl(244, 38%, 16%);
    border-radius: 10px;
  }
  .stats__image {
    grid-row: 1/2;
    grid-column: unset;
    background-image: url('images/image-header-mobile.jpg');
  }

  .stats_content {
    grid-row: 2/3;
    grid-column: 1;
  }
}
```
### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [CSS Tricks](https://css-tricks.com/)

## Author
- Frontend Mentor - [@mr02trg](https://www.frontendmentor.io/profile/mr02trg)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

