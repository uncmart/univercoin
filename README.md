### univercoin UNC 万用币
website：http://uncmart.com/

### Dependencies
* GCC 4.7.3 or later     (http://gcc.gnu.org/)
* CMake 2.8.6 or later   (http://www.cmake.org/)
* Boost 1.55 or later    (http://www.boost.org/)

**1. Clone wallet sources**

```
git clone https://github.com/uncmart/univercoin.git
```

**2. Build**
### On ubuntu 14.04

```
mkdir build && cd build && cmake .. && make
```


### On Windows
Dependencies: MSVC 2017, CMake 3.10.2 or later, Boost 1.59. You may download them from:

MSVC 2017: http://www.microsoft.com/
Came: http://www.cmake.org/
Boost: https://nchc.dl.sourceforge.net/project/boost/boost-binaries/1.59.0/boost_1_59_0-msvc-14.0-64.exe


To build, change to a directory where this file is located, set Qt PATH in CMakeLists.txt:
set (CMAKE_PREFIX_PATH "C:\\Qt\\5.9\\msvc2017_64")

and run these commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 15 Win64" ..
```

And then use MSVC 2017 open “.sln" file, do Build.
Good luck!


