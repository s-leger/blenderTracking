# blenderTracking
Refine tracking solution

When solving for camera motion, setting track weight according reprojection error allow pretty fast and good convergence.
Here is a script to automatically set weight of all tracks according error in a single click. 
Basically this allow you to **choose the wanted solution error** and setup tracks according.
Perfect for automatically tracked movies, with many tracks. 

*Even a bad track may have a good influence with correct weight.*

## Installation:

* Setup the plugin as usual
* Find it under movie clip -> Tools -> Solve -> Refine solution.

## Usage:

* Start to Solve your motion as usually
* Choose your target solution error, eg: 0.3 
* Refine your camera motion path solution.
