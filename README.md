StarEngine [2D] Game Engine
==========

Crossplatform C++11 2D Game Engine for Windows and Android games

## NOTE

This project has been stopped. You can find the successor StarEngine project [here](https://github.com/StarEngine/engine). This repository stays alive as a reference, but should not be used anymore.

## Developers
* [C�dric Van De Walle (Vanatis)](http://vdwcedric.com/)
* [Glen De Cauwsemaecker (GlenDC)](http://www.glendc.com/)
* [Pieter Vantorre (NuclearCookie)](http://pietervantorre.com/)
* [Simon Vanhauwaert (Syvion)](http://www.simonvanhauwaert.com/)

## Stable (master): In Development 
* As long as this branch is in development you should always use [the develop engine version](https://github.com/GlenDC/StarEngine/commits/develop), as this branch gets updated daily!

## Unstable (develop): v0.0.2
Patch Notes:
* [19/11/2013] 0.0.1: 
  * Initial version of the engine;
  * From now on we'll record patch notes;
  * The official repository is now also protected and people can start forking and improve the engine;
* [20/11/2013] 0.0.2:
  * The GLM classes and functions have been embedded in the engine;
    * Math functions can be found in the Helpers/Math.h file;
	* Typedefs have been made for portability reasons and should be available everywhere.
	  * It is recommanded not to use any members of vector and matrices besides the data related members (e.g. x, y, z, w, ...)
  * Code reviews have been applied.
  * Camera Culling has now been implemented and can be used.
  * Components can be enabled/disabled;
  * First version of the colission system, the beginning of the physics part of the engine, has been implemented!

## License
The Star 2D Game Engine is licensed under the MIT License.
[Click here for the full license details](https://github.com/GlenDC/StarEngine/blob/master/LICENSE).
