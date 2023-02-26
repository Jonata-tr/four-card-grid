# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./design/4card.JPG)

### Links

- Solution URL: [https://github.com/Jonata-tr/four-card-grid](https://github.com/Jonata-tr/four-card-grid)
- Live Site URL: [Live Site](https://four-card-grid-iota.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned a lot about Grid. I made this project right after studying grid and how it works. It's a really cool way to organize and adjust everything on the site, making things more dynamic and agile.

And here is some code i'm proud about:

```css
.box {
  display: grid;
  grid-template-rows: repeat(2, 40px) 100px;
  grid-row: 3 / 6;
  position: relative;
  width: 400px;
  height: 252px;
  padding: 28px;
  background-color: #fff;
  box-shadow: 4px 4px 8px 0 var(--Blue-shadow);
}

.box::after {
  content: "";
  position: absolute;
  display: inline-block;
  top: -4px;
  width: 400px;
  height: 6px;
  border-radius: 4px 4px 0 0;
}
```
