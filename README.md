angular-hex-colorpicker
=============================

A simple, configurable colorpicker directive for AngularJS
No dependency on jQuery or additional stylesheets are required.<br />
Does not support alpha, and will remain simple.<br />

<a href="http://jsfiddle.net/twler/hx1Ltkfx/" target="_blank">Demo page</a>

Installation
===============================
Copy `angular-dab-colorpicker.js` and add the dependency to your app, for instance:

    angular.module('myApp', ['dab.colorpicker'])

Usage
===============================

```html
<div dab-colorpicker dab-model="demo.dabModel" dab-height="{{ demo.dabHeight }}" dab-width="{{ demo.dabWidth }}" dab-radius="{{ demo.dabRadius }}" dab-vertical="{{ demo.dabVertical }}" dab-rotate="{{ demo.dabRotate }}"></div>
```

Eazy peazy
