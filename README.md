PlanetSide 2 Point Mapper
=========================

A small command line tool to map out points based on PlanetSide 2's coordinate system.
```
compile.lua <listfile> <baseimage> [outfile] [legendfile]
* listfile : Point list file name relative to the 'list' folder.
* baseimage : Base image file name relative to the 'res/base' folder.
* outfile (opt) : Output file name. Defaults to 'out.jpg'.
* legendfile (opt) : Legend image file name. Defaults to 'legend.png'.
```
Released under zlib/libpng public license.


Dependencies
------------

Requires an installation of Lua/LuaJIT with FFI functionality. Binaries provided for Windows x86.

* [CSFML](http://www.sfml-dev.org/)
* [LuaJIT](http://luajit.org/)
* [LSFML](https://github.com/ief015/LSFML)


Credits
---------------
Thanks to VanuLabs for the high-res continental maps, and to all contributing pumpkin hunters!