# Object GUI Library
Object GUI Library is library made to unify making GUI on most popular
frameworks and libraries using C++. Now it's only available for Qt5,
GTK and Win32 (Windows.h).
## Installing
1. Download source
2. Unpack it, and type `make xx`, where xx is qt5, gtk or win32, depending on needs.
3. After installtion type `make install`, to copy headers and libraries.
**NOTE: If compiling on Windows, please use Makefile-win instead of Makefile, and specify compiler path in variable COMP_PATH.**
## Including
Include ogl-xx.hpp, where xx is framework which was installed.
## License
OGL is distributed under BSD 2-clause license.

