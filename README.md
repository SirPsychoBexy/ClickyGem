# Basic C++ SDL project

This project is a basic C++ SDL project that uses CMake as a build system.

## Dependencies

- Git
- C/C++ Compiler (gcc, g++, ...)
- CMake
- SDL2 library

**On Debian/Ubuntu based distributions, use the following command:**

```sh
sudo apt install git-core build-essential pkg-config cmake cmake-data libsdl2-dev
```

**Optional packages:**

- SDL2_image library
- SDL2_ttf library
- SDL2_gfx library

```sh
sudo apt install libsdl2-image-dev libsdl2-ttf-dev libsdl2-gfx-dev
```

## Build instructions

```sh
# Clone this repo
git clone git@gitlab.com:aminosbh/basic-cpp-sdl-project.git
cd basic-cpp-sdl-project

# Create a build folder
mkdir build
cd build

# Build
cmake ..
make

# Run
./basic-cpp-sdl-project
```

***Note:*** To use SDL2_image, SDL2_ttf or SDL2_gfx, you should uncomment
some instructions in the CMakeLists.txt file and re-execute `cmake ..` and `make`

## License

This project is distributed under the terms of the MIT license
[&lt;LICENSE&gt;](LICENSE).

