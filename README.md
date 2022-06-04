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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](design/screenshot_desktop.png)
![](design/screenshot_mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS custom properties
- Bootstrap V5.1.3
- Bootstrap Grid

### What I learned

I've learned more about Bootstrap Grid system, discovered about Gutter classes, and reordering the columns.

```html
<div class="container-fluid">
  <div class="row">

    <div class="col-sm-6 p-0 image-container order-sm-last">
      ...
    </div>

    <div class="col-sm-6 insight-col d-block my-auto">
      <div class="row stats-area gy-4">
        ...
      </div>
    </div>
    
  </div>
</div>
```

### Useful resources

- [Bootstrap - Grid System](https://getbootstrap.com/docs/5.1/layout/columns/#reordering)
- [Bootstrap - Gutter Classes](https://getbootstrap.com/docs/5.1/layout/gutters/)
- [Bootstrap - Reordering Columns](https://getbootstrap.com/docs/5.1/layout/columns/#reordering)

## Author

- GitHub - [SYadanar](https://github.com/SYadanar)
- Frontend Mentor - [@SYadanar](https://www.frontendmentor.io/profile/SYadanar)