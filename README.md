WebAssets for OpenSimulator
===========================

This small set of php functions provides easy access to OpenSimulator
assets, adding another level of caching, thus limiting load on given
asset server.

Typical usage includes web publication of avatar's profile pictures, library and user
stored textures, region maptiles, user and regions/lands snapshots.


classes availability
--------------------

oo classes are currently beeing worked on ('objectoriented-staging' branch). Merge will occur upon completion/successful tests.

Tested on
---------
Updated and tested on September 2010, with following software :

WebServer :

 * Apache 2.2.16

 * Php 5.2.14

 * imagick 2.3.0 PECL package

 * ImageMagick 6.6.2.5 with jpeg2k delegate
 running on linux 2.6.34, gentoo 64bits

OpenSimulator AssetServer :

 * OpenSimulator 0.6.9 (grid mode) both from a local grid and current osgrid.org GRID.

Installation
------------
See included **INSTALL** file.


