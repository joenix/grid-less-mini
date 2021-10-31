# grid-less

## install

```bash
yarn add grid-less-mini
# or
npm i grid-less-mini
```

## how to use

### Usage 1

```sass
// in less file
@import "~grid-less-mini/index.less";
```

```html
<div class="grid-row-7">
  <span class="grid-col-3">A</span>
  <span class="grid-col-4">B</span>
</div>
```

### Usage 2

```sass
// in less file
@import "~grid-less-mini/grid.less";

// spacing of grid
@grid-unit: 20px;

// max fences of grid
.grid-loop( 24 );
```
