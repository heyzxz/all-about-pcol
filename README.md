# All About PCOL
PCOL is a WebGL based 3D billiards game. And this repo is for providing informations and collecting user feedback.

![pcol-poster](./img/pcol-poster.jpg)

**[Play Now](http://www.heyzxz.me/pcol)** (Currently only snooker available.)

## Bug Report / Feedback
Please use **[Issues](https://github.com/heyzxz/all-about-pcol/issues)** for bug report and questions/feedback.

If you don't wanna make your question public, here is my email: [heyzxz@gmail.com](mailto:heyzxz@gmail.com).

## About The Game
* **[[Technical Specs]](#technical-specs)**
* **[[Known Issues]](#known-issues)**
* **[[FAQ]](#known-issues)**


## Technical Specs
This game is developed in pure javascript. The graphics part is based on [Babylonjs](https://github.com/BabylonJS/Babylon.js) Engine.

### File Size
≈6M first load without browser cache.

### Compatibility
It's mainly targeting for supporting the latest versions of these browsers below:
* **Firefox** ( Tested on both win & mac )
* **Google Chrome** ( Tested on both win & mac )
* **Safari** ( Tested on mac )
* **Edge** ( Tested on win )

**IE11?** - sorry no...

**Other WebGL-supported browsers?** - not test yet...

### Recommended Browsers
* Browsers with **WebGL 2.0** support are recommended. See [here](https://caniuse.com/#search=webgl2) for which.
* According to my personal tests on mac (mid 2015, i7, AMD Radeon R9 M370X 2048 MB), **Firefox(60.0.2 (64-bit))** is the winner.
### Mobile Browsers?
Currently no... Computations are too heavy for them.

*Please note that as it is based on WebGL, performance/compatibility is also depend on the GPU performance of your device.*

## Known Issues
* **Rules of Snooker needs to be improved.** Includes:
	* Require the fouling player to take a shot again.
	* Jump shots Fouls. Currently it is just allowed.
	* Free balls. Currently don't have.
	* State the desired color when shoting color balls. (I'm still thinking about how...)

* **Some physical parameters needs to be tweaked.**

### FAQ
TODO

