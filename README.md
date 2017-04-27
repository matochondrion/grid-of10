# grid-of10
An add-on module for Basscss. Includes responsive 10-column grid classes (so 5-columns as well). The default Basscss 12-column grid is great, but sometimes a **5 or 10 column layout** is needed.


## 10-column layout

```html
<div class="flex flex-wrap">
  <div class="gridof10-10 border">.gridof10-10</div>
  <div class="gridof10-10 border">.gridof10-10</div>
  <div class="gridof10-10 border">.gridof10-10</div>
  <div class="gridof10-10 border">.gridof10-10</div>
  <div class="gridof10-10 border">.gridof10-10</div>
  <div class="gridof10-10 border">.gridof10-10</div>
  <div class="gridof10-10 border">.gridof10-10</div>
  <div class="gridof10-10 border">.gridof10-10</div>
  <div class="gridof10-10 border">.gridof10-10</div>
  <div class="gridof10-10 border">.gridof10-10</div>
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
  <div class="gridof10-1 sm-gridof10-2 border">.gridof10-1 .sm-gridof10-2</div>
  <div class="gridof10-1 sm-gridof10-2 border">.gridof10-1 .sm-gridof10-2</div>
  <div class="gridof10-1 sm-gridof10-2 border">.gridof10-1 .sm-gridof10-2</div>
  <div class="gridof10-1 sm-gridof10-2 border">.gridof10-1 .sm-gridof10-2</div>
  <div class="gridof10-1 sm-gridof10-2 border">.gridof10-1 .sm-gridof10-2</div>
</div>
```

## Responsive - grid-of10 with Basscss Grid
Combine grid-of10 with the 12-column Basscss Grid classes in responsive layouts. The default size is 100% based on the Basscss Grid class, `.col-12`. Apply a 5-column grid with  grid-of10, from the medium breakpoint and up with the `.md-gridof10-2` class.

```html
<div class="flex flex-wrap">
  <div class="col-12 md-gridof10-2 border">.md-gridof10-2</div>
  <div class="col-12 md-gridof10-2 border">.md-gridof10-2</div>
  <div class="col-12 md-gridof10-2 border">.md-gridof10-2</div>
  <div class="col-12 md-gridof10-2 border">.md-gridof10-2</div>
  <div class="col-12 md-gridof10-2 border">.md-gridof10-2</div>
</div>
```

---

MIT license
