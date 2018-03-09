# Assignment_1
COSC1187 Assignment 1

Copyright 2018 Tim Davis and Jesse Buhagiar

## Build Instructions
###Linux

Install _cmake_ and _Doxygen_

Make sure you have GLUT, glu and OpenGL installed on your system (most likely mesa-libgl etc)

Type _cmake CMakeLists.txt_ from the root project directory and hit enter

Type _make_ and hit enter

_cd_ to the _/bin/_ directory and then run the binary.

###Windows

_Note_: You really should be using MinGW w64 on a Windows based system. Make sure it's in your path. 

Run build.bat

Enter the directory where your library/include directories are (e.g C:/C++Libs)

Hit enter

Type _mingw32-make_

Go to the binary directory and you should be able to run the executable

_Note_: You may and probably _will_ get linker errors on the first try; building on Windows is a tad bit complicated.
