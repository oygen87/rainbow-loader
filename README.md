# Rainbow Loader 

[![npm version](https://badge.fury.io/js/rainbow-loader.svg)](https://badge.fury.io/js/rainbow-loader)

### Install

`npm i rainbow-loader`

### Import stylesheet

`import "rainbow-loader/css/rainbow-loader.css"`

### Usage

`<div class="rainbow-loader"></div>`

### Override

You can override `.rainbow-loader` class in your own css files.

Example to change height to be 100% of parent element instead of a fixed 0.2rem, and to a slower speed : 

```
.rainbow-loader {
    height: 100% !important; /* default is 0.2rem */
    animation-duration: 8s !important; /* default is 2s */
}
```

### Demo

[https://codepen.io/oygen/pen/WNeOXXN](https://codepen.io/oygen/pen/WNeOXXN)
