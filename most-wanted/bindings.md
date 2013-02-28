# Most Wanted Native Bindings

These are the native libraries that are most wanted as NativeCall bindings
rather than as Perl 6 source ports.  Often this is because the native library
offers performance or security guarantees that would be difficult or
impossible to provide in HLL code.  In other cases, it is because the library
provides such complex or finicky functionality that it could not be reproduced
in a correct new implementation without great effort -- effort that could be
better spent on [other most-wanted tasks](README-wanted.md).


## Archives and Compression

* zlib
* bzip2
* 7zip (7z.so/lib7zip)


## Databases

* DBD::
  + MySQL
  + Postgres
  + SQLite


## Image processing

* Canvas and/or GD
* Charting/Graphing
* ImageMagick or similar


## Security

* openssl (WIP: [SSL](https://github.com/grondilu/openssl/))
* ssh


## User interfaces

* Terminal
  + curses (WIP: [NCurses](https://github.com/azawawi/perl6-ncurses/))
  + readline
* GUI
  + Qt
  + Gtk
* 2D Graphics
  + SDL (WIP: [SDL](https://github.com/PerlGameDev/SDL6/))
* 3D Graphics
  + OpenGL

## Other

* XML
  + Libxml2
  + Libxslt
