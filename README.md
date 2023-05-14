# NES Emulator
### Compiling
Requirements:
* SFML 2.0+ development headers and library
* C++11 compliant compiler
* CMake build system

Compiling is done with cmake, run cmake on the project directory with CMAKE_BUILD_TYPE=Release
and you'll get a Makefile (or equivalent for your platform) which you can use to compile the emulator

### Controller

Default Bindings (Can be changed in keybindings.conf):

**Player 1**

 Button        | Mapped to
 --------------|-------------
 Start         | Return/Enter
 Select        | Right Shift
 A             | J
 B             | K
 Up            | W
 Down          | S
 Left          | A
 Right         | D


**Player 2**

 Button        | Mapped to
 --------------|-------------
 Start         | Numpad 9
 Select        | Numpad 8
 A             | Numpad 5
 B             | Numpad 6
 Up            | Up
 Down          | Down
 Left          | Left
 Right         | Right
