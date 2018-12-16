[![Gzip Size](https://img.badgesize.io/https://unpkg.com/infinity-css-grid@1.0.1/grid.min.css?compression=gzip)](https://unpkg.com/infinity-css-grid@1.0.1/grid.min.css)

<p align="center"><img src="logo.png" /></p>

<h1 align="center"> Infinity CSS Grid </h1>

<p align="center"> Ultra minimal fluid Flex Grid. </p>

<hr/>

<p> Infinity CSS Grid is around 0,1 Kb CSS for making any number of rows. </p>

<p> Just add any number of .row in the .column: </p>

```html
// For 3 rows:

<div class="column">
  <div class="row">1</div>
  <div class="row">1</div>
  <div class="row">1</div>
</div>
```

<p>The CSS code is based on this: </p>

```css
.column{display: flex; flex-flow: row wrap}

.row{flex:1}
```
<h3>Installation </h3>

<p>Just simply download the project or: </p>


```shell
$ npm i infinity-css-grid
```

```html
<link rel="stylesheet" href="https://unpkg.com/infinity-css-grid@1.0.1/grid.css">
```


<h3>License</h3>

This project is licensed under the MIT License
