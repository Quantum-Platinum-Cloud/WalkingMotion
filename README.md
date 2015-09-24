# WalkingMotion

WalkingMotion is a class library that generates 2D pseudo human walking motion by a combination of a couple of trigonometric functions.

## Demo

See the [demo page](https://fukuchi.org/works/shortshort/WalkingMotion/).

## Synopsis

An instance of the `WalkingMan` class has the following `PVector` variables:

* `head`
* `shoulder`
* `waist`
* `arms[][]`
* `legs[][]`

`head`, `shoulder` and `waist` are explicit. `arms[0][0]` provides the position of the joint of his right arm, and `arms[0][1]` provides the position of his right hand. `legs[1][0]` provides the joint of his left leg, and so on.

In order to update the posture of the walking man, call `update(float phase)`. Walking motion is a periodic function for phase 0.0-1.0.

## LICENSE

WalkingMotion is released under the terms of Creative Commons Zero (CC0 1.0). You can copy, modify, distribute and perform the work, even for commercial purpose, all without asking permission. See the LICENSE file for the details.
