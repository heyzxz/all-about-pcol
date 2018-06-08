# All About PCOL
PCOL is a WebGL based 3D billiards game. And this repo is for providing informations and collecting user feedback.

![pcol-poster](./img/pcol-poster.jpg)

**[Play Now](http://www.heyzxz.me/pcol)** (Currently only snooker available.)

## Bug Report / Feedback
For bug report and **PUBLIC** feedback/questions, please [open a new issue.](https://github.com/heyzxz/all-about-pcol/issues)
If you don't wanna make your questions public, here is my email: [heyzxz@gmail.com](mailto:heyzxz@gmail.com).
For bug report, firstly please make sure it is not included in the **[Known Issues](https://github.com/heyzxz/all-about-pcol#known-issues)** below.
## About The Game

## Technical Specs
Developed in pure javascript. Graphics part is based on [Babylonjs](https://github.com/BabylonJS/Babylon.js) Engine.

### Compatibility
I mainly targets for supporting these desktop browsers below:
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
1. **Rules of Snooker needs to be improved.** Includes:
	1. There is no way to require the fouling player to take a shot again.
	1. Jump shots Fouls. Currently it is just allowed.
	1. Free balls. Currently don't have.
	1. There is no way to state the desired color when shoting color balls. I'm still thinking about how to do this...

1. **Some Physical parameters needs to be tweaked.**

### FAQ
TODO
