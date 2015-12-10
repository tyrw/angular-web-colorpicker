angular-web-colorpicker
==

A simple, configurable web colorpicker directive for AngularJS.<br />
No dependency on jQuery or additional stylesheets are required.<br />
Does not support alpha (though it would be easy to add yourself).<br />

<h2><a href="http://jsfiddle.net/twler/hx1Ltkfx/" target="_blank">Demo page</a></h2>

Installation
==
Copy `angular-web-colorpicker.js` and add the dependency to your app, for instance:

    angular.module('myApp', ['web.colorpicker'])

Usage
==

```html
<div web-colorpicker
  dab-model="myModel"
  dab-height="{{ myHeight }}"
  dab-width="{{ myWidth }}"
  dab-radius="{{ myRadius }}"
  dab-rotate="{{ myRotate }}"
  dab-vertical="{{ myVertical }}"
  show-grayscale="true">
</div>
```

Options
--

input | use | unit
:----------|:---------|:---------
`dab-model` | hex color code to be selected | -
`dab-height` | height of the dabs in the colorpicker | px
`dab-width` | width of the dabs in the colorpicker | px
`dab-radius` | radius of the dabs in the colorpicker | %
`dab-rotate` | rotation angle of the dabs in the colorpicker | deg
`dab-vertical` | vertical compression of the colorpicker | px
`show-grayscale` | if true, show the grayscale dabs | -
