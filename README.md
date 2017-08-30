# iris-noUiSlider

noUiSlider is lightweight JavaScript range slider.

- **No dependencies**
- All modern browsers and [IE9+](#browser-support) are supported
- Fully **responsive**
- **Touch support** on Android, iOS and Windows devices
- Tons of [examples](https://refreshless.com/nouislider/examples) and answered [Stack Overflow questions](https://stackoverflow.com/questions/tagged/nouislider)

Documentation
-------
An extensive documentation, including **examples**, **options** and **configuration details**, is available here: [noUiSlider documentation](https://refreshless.com/nouislider/).

npm [(package)](https://www.npmjs.com/package/nouislider)
---
`npm install nouislider --save`

Browserify
----------
This library is [UMD](https://github.com/umdjs/umd) compatible, so you can use it in this way:

```javascript
var noUiSlider = require('nouislider');

var slider = document.getElementById('slider');

noUiSlider.create(slider, {
  start: 40,
  connect: "lower",
  range: {
    min: 0,
    max: 100
  }
});
```

Browser support
---------------

All major browsers are supported. **To support IE8** you'll need to shim several ES5 features.

You can use [polyfill.io](https://cdn.polyfill.io/v2/docs/) to easily do so:

```html
<meta http-equiv="X-UA-Compatible" content="IE=Edge">
<!--[if lte IE 8]>
<script src="https://cdn.polyfill.io/v2/polyfill.min.js"></script>
<![endif]-->
```
