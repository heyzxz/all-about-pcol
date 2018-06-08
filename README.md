# All About PCOL
PCOL is a WebGL based 3D billiards game. And this repo is for providing informations and collecting user feedback.

![pcol-poster](./img/pcol-poster.jpg)

**[Play Now](http://www.heyzxz.me/pcol)** (Currently only snooker available.)

## Bug Report / Feedback
For bug report and public feedback/questions, you can [open a new issue.](/issues/new) If you don't wanna make your question public, here is my email: [heyzxz@gmail.com](mailto:heyzxz@gmail.com).

Please prevent submitting duplicated questions by [searching relevant issues](/issues) firstly and also reading the [Know Issues](#known-issues) section below.

## About The Game
* **[[Technical Specs]](#technical-specs)**
* **[[Known Issues]](#known-issues)**
* **[[FAQ]](#known-issues)**


## Technical Specs
It is developed in pure javascript. Graphics part is based on [Babylonjs](https://github.com/BabylonJS/Babylon.js) Engine.

### Compatibility
I mainly target for supporting these desktop browsers below:
* **Firefox** ( Tested on both win & mac )
* **Google Chrome** ( Tested on both win & mac )
* **Safari** ( Tested on mac )
* **Edge** ( Tested on win )

( All of the above are latest versions by June, 2018 )

For **IE11**, sorry no...

For other WebGL-supported browsers, not test yet...

### Recommended Browsers
Browsers with **WebGL 2.0** support are recommended. See [here](https://caniuse.com/#search=webgl2) for which.

According to my personal tests on my Mac (mid 2015, i7, AMD Radeon R9 M370X 2048 MB), **Firefox(60.0.2 (64-bit))** is the winner.
### Mobile Browsers?
Currently no... Computations are too heavy for them.

*Please note that as it is based on WebGL, performance/compatibility is also depend on your GPU performance of your device.*

## Known Issues
1. **Rules of Snooker needs to be improved.** Includes:
	1. Require the fouling player to take a shot again.
	1. Jump shots Fouls. Currently it is just allowed.
	1. Free balls. Currently don't have.
	1. State the desired color when shoting color balls. (I'm still thinking about how...)

1. **Some physical parameters needs to be tweaked.**

### FAQ
1. **How to improve gaming performance?**
	TODO.

