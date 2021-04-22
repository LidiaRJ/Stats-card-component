# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Build out a Stats previous card component. Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

[Screenshot_1](../stats-preview-card-component-main/myScreenshots/Desktop_stats_component_LRJ)
[Screenshot_2](../stats-preview-card-component-main/myScreenshots/Mobile_stats_component_LRJ)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Nesting elements with different structures to showcase the content in different browser sizes. Applying breaklines without usin the <br> tag but breaking down sentences where I needed to on CSS. 

Code snippets:

```html
<p>
  <span id="break">Discover the benefits of data </span> <span id="break">analytics and make better decisions</span><span id="break">regarding revenue, customer </span><span id="break">experience, and overall efficiency.</span>
</p>
```
```css
#break::after {
    content: "\a";
    white-space: pre;
}
```

### Useful resources

-  I've used previous projects I built to help writing the structure of the stats component.

## Author

- Website - [Lidia Ruiz Jimeno](https://www.behance.net/Lidiarjimeno)
- Frontend Mentor - [@LidiaRJ](https://www.frontendmentor.io/profile/LidiaRJ)
- Github - [@LidiaRJ](https://github.com/LidiaRJ)
- Codepen - (https://codepen.io/lilyrj)

