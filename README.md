# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Build out the project to the designs provided

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/franziskawich/profile-card-component/](https://github.com/franziskawich/profile-card-component/)
- Live Site URL: [https://franziskawich.github.io/profile-card-component/](https://franziskawich.github.io/profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS (saved as CSS)
- Flexbox

### What I learned

I learned how to include two background images at once and how to position both of the images with the help of the background-position property.

```css
body {
  background-image: url(../images/bg-pattern-top.svg), url(../images/bg-pattern-bottom.svg);
  background-position: right 50vw bottom 50vh, left 50vw top 50vh;
  }
```

I realized that it is a little bit easier to use hsl color values instead of rgba when needing a darker or lighter version of a current color.

Although I did not use it in the challenge, I found out about the shorthand property place-items (align-items, justify-items).


### Continued development

I had some problems with centering the user image. I ended up using flexbox and transform, but I'm not sure if this is the best solution. I used vh and vw units several times and it worked fine, but I think I should use them more often to know when it is right to use them. I read somewhere that they are more associated with typography.


### Useful resources

- [CSS-Tricks: Using multiple backgrounds](https://css-tricks.com/css-basics-using-multiple-backgrounds/) - This helped me with including two background images.


## Author

- Frontend Mentor - [@franziskawich](https://www.frontendmentor.io/profile/franziskawich)
- freeCodeCamp - [Franziska Wich](https://www.freecodecamp.org/fcc35fab9df-6b8c-445e-8aec-36ee00e99ba0)

