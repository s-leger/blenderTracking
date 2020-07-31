# blenderTracking
Refine tracking solution

When solving for camera motion, narrowing down solve error by hand may be a really frustrating task. 
Setting track weight according reprojection error solve this issue for camera motion tracking.
Here is a script to automatically set weight of all tracks according error in a single click.

Basically this allow you to **choose the wanted solution error** and get it within a single click,
even with poor tracks (automatic detected feature).

Perfect for automatically tracked movies, with many tracks. 

*Even a bad track may have a good influence with correct weight.*

## Installation:

* This addon is part of 2.79 / 2.8 release, you only must enable in addon preferences.
* Find it under movie clip -> Tools -> Solve -> Refine solution.

## Usage:

![Ui](https://github.com/s-leger/images/blob/master/refine.png)  

* Start to Solve your motion as usually
* Choose your target solution error, eg: 0.3 
* Refine your camera motion path solution.
