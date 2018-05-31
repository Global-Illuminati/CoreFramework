# CoreFramework

This code constitutes the common core framework for implementing Global Illumination techniques. The code is very barebones and supports:

 - Basic forward rendering with directional light shadows & environment mapping
 - Some basic debug rendering (e.g. `renderTextureToScreen` & rendering of probe locations)
 - Asynchronous .obj model & texture loading
 - GUI & basic statistic for things such as frame time and fps

The other repositories in this GitHub organization are based off of this code, but with time they have deviated from it. This code is kept here as is for future reference.

## Controls

First-person WASD controls, plus Q and E for rolling. Press *ctrl* to take control of the camera and *escape* to release control.

## Dependencies

 - For slightly simplified WebGL 2.0 usage: [PicoGL.js](https://tsherif.github.io/picogl.js/)
 - Vector & matrix maths: [glMatrix](http://glmatrix.net/)
  - .obj and .mtl loading: modified versions of the [three.js loaders](https://github.com/mrdoob/three.js/blob/master/examples/js/loaders/OBJLoader.js)
 - UI: [dat.gui](https://github.com/dataarts/dat.gui)
 - Basic statistics and graphs: [stats.js](https://github.com/mrdoob/stats.js/)

## License

Copyright 2018 Marcus Bertilsson, Hannes von Essen, Daniel Hesslow, Niklas Jonsson, Simon Moos, Olle Persson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
