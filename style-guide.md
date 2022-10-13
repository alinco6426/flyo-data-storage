<!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>.attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style># Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary
.bubble{
    width: 120px;
    height: 80px;
    background: blue;
    position: absolute;
    border-radius: 12px;
    top: 50px;
    left: 50px;
    transform: translate(-50px -50px);
    margin: 400px;
}
.bubble::before{
    content: counter(i love you);
    height: 0;
    width: 0;
    border-top: 13px solid transparent;
    border-right: 13px solid blue;
    border-bottom: 13px solid transparent;
    margin: 13px 0 0 --25px;
}


- Gradient: hsl(6, 100%, 80%) to hsl(335, 100%, 65%)

### Neutral

- Pale Blue: hsl(243, 100%, 93%)
- Grayish Blue: 
- Dark Blue: hsl(228, 56%, 26%)
- Very Dark Blue: hsl(229, 57%, 11%)

## Typography

### Body Copy

- Font size: 14px

### Font

- Family: [Raleway](https://fonts.google.com/specimen/Raleway)
- Weights: 400, 700
