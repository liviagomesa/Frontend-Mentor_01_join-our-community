# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: (https://github.com/liviagomesa/join-our-community)
- Live Site URL: (https://liviagomesa.github.io/join-our-community/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

1. I've learn how to import a custom font from Google Fonts to my page:
```css
@import url('https://fonts.googleapis.com/css2?family=Karla:wght@400;700&display=swap');
```

2. I've started my code with mobile devices; then, with all done, I've adapted it to bigger screens;

3. I often begin my css files with this code to anulate some default spacing:
```css
* {
    margin: 0;
    box-sizing: border-box;
}
```

4. To add opacity to a color, replace "rgb" (or "hsl") with "rgba" (or hsla) and add a third value between 0 and 1, like this:
rgba(0, 0, 0, 0.1);

5. To set margin, padding and similar properties values, the syntax is:
4 values: top right bottom left (clockwise)
2 values: vertical horizontal
1 value: same value to both sides

6. To turn a div into grid and centralize its children:
```css
display: grid;
place-content: center;
```

7. Syntax for box shadow (which creates a box behind your container/div):
box-shadow: right-displacement bottom-displacement blur-size-from-border-box offset-box-size color;

8. Use gap to add spacing between flexbox items and grid-gap for grid items.

9. When you turn a div into flex, all its children comes side-by-side; To allow line break, insert:
```css
flex-wrap: wrap;
```

10. To increase line spacing in a text, actually, you should use line-height property, like this:
```css
line-height: 1.5em;
```

11. To choose the breakpoint for my alternative design (for bigger screens), I've measured the content width (640px) and chose the immediatly bigger width from the list of devices given by Google DevTools (768px for tablets).

### Continued development

I'm not completely comfortable with the concepts and techniques below - but I think they're useful and I want to refine by focusing in future projects:
- defining page's layout (columns and rows)
- content overflow

### Useful resources

- (https://www.w3schools.com/css/css3_shadows_box.asp) - Syntax for CSS box shadow
- (https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template) - grid-template
- (https://stackoverflow.com/questions/8582176/should-border-radius-clip-the-content) - This helped me to find out why I couldn't set rounded corners for my main container: The default overflow for <div> elements is visible, so its content may be rendered outside the block box. I've changed it to hidden and the problem was solved.

## Author

- Frontend Mentor - [@liviagomesa](https://www.frontendmentor.io/profile/liviagomesa)
- LinkedIn - [@liviagomesa](https://www.linkedin.com/in/liviagomesa/)