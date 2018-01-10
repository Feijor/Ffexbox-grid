<h1 align="center">Flexbox Grid</h1>

<h5 align="center">Just another css framework for grid layout simplified but complete.</h5>

## Example

You can work in two ways.

1 - By column and sub-column:

```html
<div class="row">
  <div class="col-lg-8">
  </div>
  <div class="col-lg-2-5">
  </div>
  <div class="col-lg-1-5">
  </div>
</div>
```

This is similar to the original flexbox, divided into 12 columns divided by screen sizes xs, sm, md and lg. But each column can have 10 subdivisions so if your layout needs a column greater than 1 and less than 2 you can use col-xs-1-5 for example that represents half of a column.

2 - Breakdown by percentage: 

```html
<div class="row">
  <div class="col-p-lg-50">
  </div>
  <div class="col-p-lg-25">
  </div>
  <div class="col-p-lg-25">
  </div>
</div>
```

This is more like the css grid having division by percentage.
