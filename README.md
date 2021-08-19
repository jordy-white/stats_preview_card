# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Solution URL: https://github.com/jordy-white/stats_preview_card
- Live Site URL: https://stats-preview-card-dun.vercel.app/

## My process

I started with the mobile design, since 'mobile first' is a commonly favored approach in 2021. I scaled it up from there. I made use of SASS for the styling, since I am quite fond of using its nested properties.

### Built with

- Semantic HTML5 markup
- Flexbox
- SASS variables and nesting
- Mobile-first workflow

### What I learned

I had some trouble with the alignment and sizing of elements with this one. At desktop size, the image was tricky to work. I ended up adding an intermediate media query (between mobile and desktop viewport size) to take care of this (reducing the font size of the header solved the problem), however I feel like there are better ways to solve this problem. I will keep exploring solutions.

## Author

- Website - [Jordan White](https://github.com/jordy-white)
- Frontend Mentor - [@meatpies](https://www.frontendmentor.io/profile/meatpies)

## Acknowledgments

Special thanks to my wife (we got married 2 weeks ago), who, without knowing anything about this kind of thing, found the 'vertical-align' property, which solved an issue I had with a misaligned image!
