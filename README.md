# ENHANCE.JS

A port of [@fat](https://github.com/fat/zoom.js)'s simple jQuery plugin for image zooming – now with support for `object-fit`/`object-position` and powered by [Velocity.js](http://julian.com/research/velocity/) animations.

<img src="http://i.imgur.com/6zgfcFM.gif" width="100%"/>
### Demo

https://rawgit.com/ROUND/enhance.js/master/

### Differences

* Removes Boostrap dependency
* Adds Velocity.js dependency
* Supports `object-fit` and `object-position` CSS properties

### Known Issues (todos?)

* Causes content reflow for images without (expclitly sized) containers, including floated images
* Doesn’t work on `margin: auto` centered images
* Due to animating non-`transform` properties there is more layout/repainting on images that are cropped

![Enhance!](http://i.giphy.com/10nMEclFWTPCp2.gif)
