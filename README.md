
<p align="center">
  <a href="https://strutly.co/umbala">
    <img src="https://i.ibb.co/Hq0qnY8/logo.png" alt="Umbala logo" width="275">
  </a>
</p>
<h4 align="center">Lightweight and powerful css framework</h4>


## Table of umbala.css

- [Colors Pallet](#colors-pallet)
- [Colors](#colors)
- [Text Alignment](#text-alignment)
- [Text Direction](#text-direction)
- [Letter spacing](#letter-spacing)
- [Line Height](#line-height)
- [Text Decorations](#text-decorations)
- [Text Transform](#text-transform)
- [White space](#white-space)
- [Font Family](#font-family)
- [Font Variant](#font-variant)
- [Font Size](#font-size)
- [Font Weight](#font-weight)
- [Background Colors](#background-colors)
- [Borders](#borders)
- [Margins](#margins)
- [Paddings](#paddings)
- [Outlines](#Outlines)
- [Display](#display)
- [Position](#position)

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

## Colors

You can include the color name directly in the class attribute and it will be shown as a color property in CSS.

```html

<p class="sulu" > Welcome to umbala </p>

```

## Text Alignment

You can specify your Text Alignment by adding a simple regular css text align value after "text-".

```html

<p class="sulu text-center" > Welcome to umbala </p>

```

## Text Direction

You can specify text direction (rtl, ltr, ...) by adding "direction-..."

```html

<p class="sulu text-center direction-lft" > Welcome to umbala </p>

```

## Letter Spacing

You can add a space between latters by using "letter-spacing-..." and add a number from 1 to 25 or normal, initial

```html

<p class="sulu text-center direction-lft letter-spacing-5" > Welcome to umbala </p>

```
## Line Height

You can add a line height to your text by using "line-height-..." and add a number from 1 to 25

```html

<p class="gray line-height-4" > 
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
</p>

```

## Text Decorations

You can add a text decration to your html element by adding "text-decoration-..."

```html

<p class="black text-decoration-underline" > Welcome to umbala </p>

```
Note: you can add none value to <a> by adding "text-decoration-none".

## Text Transform

You can specify a transform for your text by adding a simple class "uppercase, lowercase, capitalize".

```html

<p class="red capitalize" > Welcome to umbala </p>

```

## White Space

You have the ability to add a white space to your html element by add "white-space-...".

```html

<p class="red white-space-wrap" > 
 This example demonstrates the white-space property. You can see the result of the different white-space properties by  clicking on one of the properties on the left.  
</p>

```
## Word Spacing

You can add a word spacing by specify a value from 1 to 25 or normal in "word-spacing-...".

```html

<p class="red word-spacing-3" > 
 This example demonstrates the white-space property. You can see the result of the different white-space properties by  clicking on one of the properties on the left.  
</p>

```

## Font Family

You can specify a font family to your font by add "font-...".

```html

<p class="black font-serif" > 
 This example demonstrates the white-space property. You can see the result of the different white-space properties by  clicking on one of the properties on the left.  
</p>

```
Note: this is a list for all Google fonts included on umbala

```bash

$ roboto
$ open-sans
$ Lato
$ montserrat
$ poppins
$ oswlad
$ playfair display
$ cairo
$ tajawal
$ amiri
$ almarai
$ aref-ruqaa
$ mirza

```

## Font Variant

You can add to your font a font-variant by adding "font-variant-.."

```html

<p class="sulu font-variant-normal" > 
 This example demonstrates the white-space property. You can see the result of the different white-space properties by  clicking on one of the properties on the left.  
</p>

```

## Font Size

You can add font size from 1px to 25px or some regulrar UI sizes by adding "font-size-..."

```html

<p class="gray font-size-16" > 
 This example demonstrates the white-space property. You can see the result of the different white-space properties by  clicking on one of the properties on the left.  
</p>

```

```html
// Some regular UI sizes


font-size-small

font-size-title

font-size-paragraph

font-size-thumb

font-size-big

font-size-big-plus

```

## Font Weight

You have some font wight you can add to your html like the regular css ones from 100 to 900 and normal, bold, bolder, lighter by adding "font-weight-..."

```html

<p class="gray font-weight-600" > 
 This example demonstrates the white-space property. You can see the result of the different white-space properties by  clicking on one of the properties on the left.  
</p>

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


## Paddings

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

## Outlines

You can add outline to your html by add (color, width, style, offset) proprety after "outline-...".

```html

<div class="border-red border-width-3 border-style-solid  outline-red outline-width-2 outline-style-dotted outline-offset-5">
  <p class="sulu margin-5" > Welcome to umbala </p>
</div>

```


## Display

You can specify the display in your html style by adding "dispaly-..."

```html

<div class="background-red display-none">
  <p class="sulu margin-5" > none display exemple </p>
</div>

```
```html

<div class="background-red display-block">
  <p class="sulu margin-5" > Block display exemple </p>
</div>

```
## Position

You can add position value to your code by specify "position-..."

```html

<div class="background-red position-absolute">
  <p class="sulu margin-5" > "position: absolute" exemple </p>
</div>

```
### Top - Bottom - left - right

You can specify a top, bottom, left, right value by add from 1px to 25px, or by percent 5, 10, 15, ..., 100 or auto

```html

<div class="background-red position-absolute top-auto">
  <p class="sulu margin-5" > exemple for top: auto </p>
</div>

```


```html

<div class="background-red position-absolute bottom-12">
  <p class="sulu margin-5" > exemple for bottom: 12px </p>
</div>

```

```html

<div class="background-red position-absolute left-25per">
  <p class="sulu margin-5" > exemple for left: 25% </p>
</div>

```