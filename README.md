# grid-of10
An add-on module for Basscss. Includes responsive 10-column grid classes (so 5-columns as well). The default Basscss 12-column grid is great, but sometimes a **5 or 10 column layout** is needed.


## 10-column layout

```html
<div class="flex flex-wrap">
  <div class="gridof10-1 border">.gridof10-1</div>
  <div class="gridof10-1 border">.gridof10-1</div>
  <div class="gridof10-1 border">.gridof10-1</div>
  <div class="gridof10-1 border">.gridof10-1</div>
  <div class="gridof10-1 border">.gridof10-1</div>
  <div class="gridof10-1 border">.gridof10-1</div>
  <div class="gridof10-1 border">.gridof10-1</div>
  <div class="gridof10-1 border">.gridof10-1</div>
  <div class="gridof10-1 border">.gridof10-1</div>
  <div class="gridof10-1 border">.gridof10-1</div>
</div>
```

## 5-column layout

```html
<div class="flex flex-wrap">
  <div class="gridof10-2 border">.gridof10-2</div>
  <div class="gridof10-2 border">.gridof10-2</div>
  <div class="gridof10-2 border">.gridof10-2</div>
  <div class="gridof10-2 border">.gridof10-2</div>
  <div class="gridof10-2 border">.gridof10-2</div>
</div>
```

## Responsive Grid
Use Basscss breakpoint styles to change the grid at different screen widths for responsive layouts.

Apply a 5-column grid from the small breakpoint and up with the `.sm-gridof10-2` class.

```html
<div class="flex flex-wrap">
  <div class="gridof10-10 sm-gridof10-2 border">.gridof10-10 .sm-gridof10-2</div>
  <div class="gridof10-10 sm-gridof10-2 border">.gridof10-10 .sm-gridof10-2</div>
  <div class="gridof10-10 sm-gridof10-2 border">.gridof10-10 .sm-gridof10-2</div>
  <div class="gridof10-10 sm-gridof10-2 border">.gridof10-10 .sm-gridof10-2</div>
  <div class="gridof10-10 sm-gridof10-2 border">.gridof10-10 .sm-gridof10-2</div>
</div>
```

## Responsive - grid-of10 with Basscss Grid
Combine grid-of10 with the 12-column Basscss Grid classes in responsive layouts. The default size is 100% based on the Basscss Grid class, `.col-12`. Apply a 5-column grid with  grid-of10, from the medium breakpoint and up with the `.md-gridof10-2` class.

```html
<div class="flex flex-wrap">
  <div class="col-12 md-gridof10-2 border">.col-12 .md-gridof10-2</div>
  <div class="col-12 md-gridof10-2 border">.col-12 .md-gridof10-2</div>
  <div class="col-12 md-gridof10-2 border">.col-12 .md-gridof10-2</div>
  <div class="col-12 md-gridof10-2 border">.col-12 .md-gridof10-2</div>
  <div class="col-12 md-gridof10-2 border">.col-12 .md-gridof10-2</div>
</div>
```

---
## Install

```sh
npm --save-dev grid-of10
```

## CDN Link
Or use the [CDN Link](https://unpkg.com/grid-of10/css/grid-of10.css)

```html
<link href="https://unpkg.com/grid-of10/css/grid-of10.css" rel="stylesheet">
```

## Usage

### PostCSS

```css
@import 'grid-of10';
```

---
## Notes
This module is meant to be an add-on for Basscss. To use, first install a Basscss project ([Basscss](https://github.com/basscss/basscss/), [Bassplate](https://github.com/basscss/bassplate), [Ace](https://github.com/basscss/ace), etc... ) with NPM, and then include `@import 'grid-of10';` in the source css file.

These examples assume the document's box-sizing has been set to _border-box_ using a method similar to [CSS-Tricks](https://css-tricks.com/box-sizing/)...

```css
html {
  box-sizing: border-box;
}
*, *:before, *:after {
  box-sizing: inherit;
}
```

---
MIT license
