Spine-EaselJS
=============

Rendering a Spine animation with EaselJS


Spine is a 2D animation software that exports animation files for multiple runtimes and file formats and it considerably helped to build out this project. There are a few javascript rendering engines out there that integrate with spine, and Pixi.js is one of them. Unfortunately, Pixi doesn’t support all Spine features and I also wasn’t able to make it run with a 2D canvas and digging into the Pixi source code is not such an easy thing to do.

When it comes to 2D canvas, my rendering engine of choice is EaselJS but I couldn’t find any spine renderer built from it so I ended up borrowing a small chunk of code from Pixi and was able to make a spine animation run very smoothly on my iPhone4 with easelJS.