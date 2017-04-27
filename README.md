# grid-of10
This module contains responsive columns based on a 10-column grid (so 5-columns as well) and compatible with Basscss. The default Basscss 12-column grid is great, but sometimes a **5 or 10 column layout** is needed.


## 10-column layout

```html
<div class="flex flex-wrap">
  <div class=".col-1of10 border">.col-1of10</div>
  <div class=".col-1of10 border">.col-1of10</div>
  <div class=".col-1of10 border">.col-1of10</div>
  <div class=".col-1of10 border">.col-1of10</div>
  <div class=".col-1of10 border">.col-1of10</div>
  <div class=".col-1of10 border">.col-1of10</div>
  <div class=".col-1of10 border">.col-1of10</div>
  <div class=".col-1of10 border">.col-1of10</div>
  <div class=".col-1of10 border">.col-1of10</div>
  <div class=".col-1of10 border">.col-1of10</div>
</div>
```

## 5-column layout

```html
<div class="flex flex-wrap">
  <div class=".col-2of10 border">.col-2of10</div>
  <div class=".col-2of10 border">.col-2of10</div>
  <div class=".col-2of10 border">.col-2of10</div>
  <div class=".col-2of10 border">.col-2of10</div>
  <div class=".col-2of10 border">.col-2of10</div>
</div>
```

## Responsive Grid
Use Basscss breakpoint styles to change the grid at different screen widths for responsive layouts.

Apply a 5-column grid from the small breakpoint and up with the `.sm-col-2of10` class.

```html
<div class="flex flex-wrap">
  <div class="col-10of10 sm-col-2of10 border">.sm-col-2of10</div>
  <div class="col-10of10 sm-col-2of10 border">.sm-col-2of10</div>
  <div class="col-10of10 sm-col-2of10 border">.sm-col-2of10</div>
  <div class="col-10of10 sm-col-2of10 border">.sm-col-2of10</div>
  <div class="col-10of10 sm-col-2of10 border">.sm-col-2of10</div>
</div>
```

## Responsive - grid-of10 with Basscss Grid
Combine grid-of10 with the 12-column Basscss Grid classes in responsive layouts. The default size is 100% based on the Basscss Grid class, `.col-12`. Apply a 5-column grid with  grid-of10, from the medium breakpoint and up with the `.md-col-2of10` class.

```html
<div class="flex flex-wrap">
  <div class="col-12 md-col-2of10 border">.md-col-2of10</div>
  <div class="col-12 md-col-2of10 border">.md-col-2of10</div>
  <div class="col-12 md-col-2of10 border">.md-col-2of10</div>
  <div class="col-12 md-col-2of10 border">.md-col-2of10</div>
  <div class="col-12 md-col-2of10 border">.md-col-2of10</div>
</div>
```

---

MIT license
