
<p align="center">
  <a href="https://strutly.co/umbala">
    <img src="https://i.ibb.co/Hq0qnY8/logo.png" alt="Umbala logo" width="275">
  </a>
</p>
<h4 align="center">Lightweight and powerful css framework</h4>


## Table of umbala.css

- [Colors Pallet](#colors-pallet)
- [Text Colors](#text-colors)
- [Background Colors](#background-colors)
- [Borders](#borders)
- [Margins](#margins)
- [Paddings](#paddings)

## Colors Pallet

We chose the most colors used in the web and we gave them a simple touch to be more compatible with the trending of UI Design and more attractive in the UX.

```text

sulu: #89F387;  // The color used as a branding color for umbala
blue: #00acff;
slate: #6a5acd;
violet: #e95ee9;
pink: #f37cb2;
orange: #e36900;
red: #FF6347;
yellow: #f9f871;
green: #008a5c;
gray: #808080;
gyeal: #CCC;
white: #ffffff;
black: #000000;


```

## Text Colors

You can include the color name directly in the class attribute and it will be shown as a color property in CSS.

```html

<p class="sulu" > Welcome to umbala </p>

```


## Background Colors

You can include the background color to your html by adding color name after "background-".

```html
<div class="background-gray">
  <p class="sulu" > Welcome to umbala </p>
</div>

```

## Borders

You can make a regular borders by define style, width, color {exemple below}

```html

<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu" > Welcome to umbala </p>
</div>

```
Note: in border width we have from 1px to 25px by add just number after "border-width-".


You can make add a border redius from 1px to 25px or you can use the percent " 5%,10%,15%,...100%" by add "border-radius-...per"

```html

//Radius by px
<div class="background-gray border-red border-width-3 border-style-solid border-radius-5">
  <p class="sulu" > Welcome to umbala </p>
</div>

//Radius by percent
<div class="background-gray border-red border-width-3 border-style-solid border-radius-5per">
  <p class="sulu" > Welcome to umbala </p>
</div>

```

Note: we have simple UI tip in Borders by add "rounded" or "unrounded"

```html
<div class="background-gray border-red border-width-3 border-style-solid rounded">
  <p class="sulu" > Welcome to umbala </p>
</div>

```

## Margins

You can make a regular margin to your html by adding a size from 1px to 25px  in "margin-"

```html

<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu margin-5" > Welcome to umbala </p>
</div>

```

Or you can specify where you want to add the margin in top, bottom, left, right, horizontal, vertical.

```html

//Top
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu margin-top-5 " > Welcome to umbala </p>
</div>

//Bottom
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu margin-bottom-5 " > Welcome to umbala </p>
</div>

//Left
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu margin-left-5 " > Welcome to umbala </p>
</div>

//Right
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu margin-right-5 " > Welcome to umbala </p>
</div>

//Horizontal
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu margin-horizontal-5 " > Welcome to umbala </p>
</div>

//Vertical
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu margin-vartical-5 " > Welcome to umbala </p>
</div>



```


## paddings

You can make a regular padding to your html by adding a size from 1px to 25px  in "padding-"

```html

<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu padding-5" > Welcome to umbala </p>
</div>

```

Or you can specify where you want to add the padding in top, bottom, left, right, horizontal, vertical.

```html

//Top
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu padding-top-5 " > Welcome to umbala </p>
</div>

//Bottom
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu padding-bottom-5 " > Welcome to umbala </p>
</div>

//Left
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu padding-left-5 " > Welcome to umbala </p>
</div>

//Right
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu padding-right-5 " > Welcome to umbala </p>
</div>

//Horizontal
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu padding-horizontal-5 " > Welcome to umbala </p>
</div>

//Vertical
<div class="background-gray border-red border-width-3 border-style-solid">
  <p class="sulu padding-vartical-5 " > Welcome to umbala </p>
</div>



```