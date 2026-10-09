# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/learning-paths/getting-started-on-frontend-mentor-XJhRWRREZd/challenge/65e6f48617e502f0b6ca3d01/start). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![](./assets/images/screenshot.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS (Flexbox)
- Mobile-first, fixed-width card layout
- Google Fonts (Figtree)

### What I learned

- `<span>` is an inline element, so vertical margins (`margin-top`/`margin-bottom`) are ignored on it. My category badge's bottom margin wasn't creating any space until I switched it to `display: inline-block`.

- Always double-check the exact font weights listed in the style guide rather than assuming common defaults (400/700). This challenge specified Figtree at 500 and 800, so the Google Fonts import URL needed to match:

```css
@import url('https://fonts.googleapis.com/css2?family=Figtree:wght@500;800&display=swap');
```

## Author

- GitHub - [@TeaJosh](https://github.com/TeaJosh)