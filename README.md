# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Faces Two Problems:

- After spending so much time in margin padding stuff finally sort that reducing the size of container will give desired layout
- Still get confused in deciding the break point in media query should use max-width or min-width but finally understood will need more practice

## My process

### Built with
Bootstrap
made one section(#threeColumns) and put everything in it

### What I learned

To get desired layout you need to reduce the size of container but it can only be achieved through media query.You cannot change it in CSS bcoz the width is predefined in bootstrap
Here is the code
```css
@media (min-width: 1200px) {
  .container {
    max-width: 900px;
  }
}
}
```

