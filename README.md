<h1 align="center">
  <img src="http://codropspz.tympanus.netdna-cdn.com/codrops/wp-content/uploads/2015/06/Collective173_enhancejs1.png"/>
</h1>

A port of [@fat](https://github.com/fat/zoom.js)'s simple jQuery plugin for image zooming – now with support for `object-fit`/`object-position`, powered by [Velocity.js](http://julian.com/research/velocity/) animations, complete with some pre-defined image cropping classes.



<h2 align="center">
  <a href="https://rawgit.com/ROUND/enhance.js/master/">
  <img src="http://i.imgur.com/6zgfcFM.gif" width="100%"/>
  :sparkles: Demo :sparkles:
  </a>
</h2>

### Differences

* Removes Boostrap dependency
* Adds Velocity.js dependency
* Supports `object-fit` and `object-position` CSS properties
* Has some classes to get you started with cropped images

### To-Dos

* Cleanup codebase (in line with zoom.js latest)
* Add optional lazy/preloading if there is a wrapping `<a>` tag to a high-resolution image
* Add more robust demo
* Synchronize Velocity.js timing with CSS animation timing
* Clean up code to allow passing a custom selector/attribute for the targeted images

### Known Issues (more todos?)

* Causes content reflow for images without (expclitly sized) containers, including floated images
* Doesn’t work on `margin: auto` centered images
* Due to animating non-`transform` properties there is more layout/repainting on images that are cropped

<p align="center">
  <img src="http://i.giphy.com/10nMEclFWTPCp2.gif"/>
</p>
