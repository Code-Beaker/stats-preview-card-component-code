# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
    - [Description](#description)
    - [Screenshots](#screenshots)
      - [Mobile Image](#mobile-image)
      - [Desktop Image](#desktop-image)
  - [The Process](#the-process)
    - [Built With](#built-with)
    - [What I learned](#what-i-learned)
    - [The code I used with `<source>`:](#the-code-i-used-with-source)
    - [CSS Grid for Responsive Design](#css-grid-for-responsive-design)
    - [Helps](#helps)
  - [Links](#links)

## Overview

### Description

This is a challenge from the **Frontend Mentor** website. Completed by Tharun-dev(Code-Beaker).

### Screenshots

#### Mobile Image

![](screenshot-mobile.png)

#### Desktop Image

![](screenshot-desktop.png)

## The Process

The process I went through to creating complete the challenge.

### Built With

- HTML5
- CSS3
- CSS Grid
- CSS Flex
- Mobile-first web design
- Responsive Design

### What I learned

- About CSS Grid and its possibilities.
- Used HTML `<source>` element with understanding.

### The code I used with `<source>`:

```html
<source srcset="./myFolder/myImageName.jpg" media="(min-width: 600px)" />
```

### CSS Grid for Responsive Design

```css
main {
  display: grid;
  grid-template-columns: 1fr;
}

@media (min-width: 600px) {
  main {
    grid-template-columns: 1fr 1fr;
  }
}
```

### Helps

I got help from the Frontend Mentor **Discord Community** in some stages.

## Links

- Live Site URL: https://code-beaker.github.io/stats-preview-card-component-code/
- GitHub Repository: https://github.com/Code-Beaker/stats-preview-card-component-code
