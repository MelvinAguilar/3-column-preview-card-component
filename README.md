<div id="top"></div>

<div align="center">

  <img src="https://www.frontendmentor.io/static/images/logo-mobile.svg" alt="frontendmentor" width="80">

  <h2 align="center">3-column preview card component solution</h2>
  <p align="center">
    <a href="https://www.frontendmentor.io/solutions/3column-preview-card-component--xxamoxSKH"><strong>Frontend Mentor Challenge</strong></a>
    <br />
    <br />
    <a href="https://3-column-preview-card-component-melvin.vercel.app/">View Demo</a>
    ·
    <a href="https://github.com/MelvinAguilar/3-column-preview-card-component/issues" target="_blank">Report Bug</a>
    ·
    <a href="https://github.com/MelvinAguilar/3-column-preview-card-component/issues" target="_blank">Request Feature</a>
  </p>
</div>

<!-- Bagdes -->
<div align="center">
  <!-- Profile -->
  <a href="https://www.frontendmentor.io/profile/MelvinAguilar">
    <img src="https://img.shields.io/badge/Profile-Melvin%20Aguilar-07043B?style=for-the-badge&logo=frontendmentor" alt="Melvin Profile">
  </a>
  <!-- Status -->
  <a href="#">
    <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" alt="Status Completed">
  </a>

</div>

#

![](./design/desktop-preview.jpg)

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

<h2 align="center">Links</h2>

- Solution URL: [3-Column Card Component (SASS + Flexbox + BEM) | Frontend Mentor](https://www.frontendmentor.io/solutions/3column-preview-card-component--xxamoxSKH)
- Live Site URL: [https://3-column-preview-card-component-melvin.vercel.app/](https://3-column-preview-card-component-melvin.vercel.app/)

<br>

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- Flex Layout
- BEM naming convention
- [SASS](https://sass-lang.com/documentation/modules) - Sass modules

### Useful resources

- [CSS Guidelines](https://cssguidelin.es/#bem-like-naming)
- [BEM naming convention](https://css-tricks.com/bem-101/)
- [BEM naming examples](https://getbem.com/naming/)

<br>

## Author

- Frontend Mentor - [@melvinaguilar](https://www.frontendmentor.io/profile/melvinaguilar)

## Acknowledgments

When using `sass` in order to build this solution

- Install `sass` if not yet installed:

```bash
npm install -g sass
```

- Run build command from command line:

```bash
sass assets/sass/main.scss assets/css/style.css
```

- If you want to edit the code and test, in the root folder of this repository, run this command from the command line:

```bash
sass --watch assets/sass/main.scss assets/css/style.css
```

## File structure

```
.
├── assets
│   ├── css
│   │   ├── style.css
│   │   └── style.css.map
│   ├── images
│   │   ├── favicon-32x32.png
│   │   ├── icon-luxury.svg
│   │   ├── icon-sedans.svg
│   │   └── icon-suvs.svg
│   └── sass
│       ├── abstracts
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base
│       │   ├── _page.scss
│       │   └── _reset.scss
│       ├── component
│       │   ├── _attribution.scss
│       │   └── _screen-reader.scss
│       ├── layout
│       │   └── _card.scss
│       └── main.scss
├── design
│   ├── active-states.jpg
│   ├── desktop-design.jpg
│   ├── desktop-preview.jpg
│   ├── mobile-design.jpg
│   └── screenshot.png
├── index.html
├── index.html
└── README.md
```
