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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![photo](screenshot(2).png)


### Links

- Solution URL: [github access](https://github.com/leongratis/profile-card)
- Live Site URL: [live preview](https://leongratis.github.io/profile-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

postioning that color image at the top left corner and bottom right corner.
How to postion an image better with not only postion relative and  position absolute

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css main{
    background-color: hsl(185, 75%, 39%);
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-left: 2rem;
    padding-right: 2rem;
    position: relative;
    overflow: hidden;
}
```
```css
.proud-of-this-css main .top-pic{
    width: 380px;
    position: absolute;
    top: -110px;
    left: -180px;
    
}
```
```css
.proud-of-this-css main .bottom-pic{
    width: 380px;
    height: auto;
    position: absolute;
    bottom: -70px;
    right: -200px;
}
```
```css
.proud-of-this-css section{
    background-color: white;
    border-radius: 10px 10px 10px 10px;
    z-index: 1;
}
```
```css
.proud-of-this-css section .image{
    display: flex;
    justify-content: center;
    text-align: center;
    position: relative;
}
```
```css
.proud-of-this-css .image img{ 
    position: absolute;
    max-width: 100%;
    height: auto;
    top: -55px;
    border-radius: 100%;
    border: 4px solid white;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

To keep  working  on a creating a responsive and mobile-first website that works on any device screensizes


### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@leongratis](https://www.frontendmentor.io/profile/leongratis)
- Twitter - [@callistusleonar](https://www.twitter.com/callistusleonar)


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
