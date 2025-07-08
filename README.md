
### Clone repository and initialise all submodules (msdf-atlas-gen -> msdfgen)
git clone --recurse-submodules https://github.com/Fahersto/OpenGL_msdf.git

## Install dependencies
### Example for vcpkg on Windows 64bit
- vcpkg install freetype:x64-windows
- vcpkg install glad:x64-windows
- vcpkg install glm:x64-windows
- vcpkg install glfw3:x64-windows

## Build and run
1. Run CMAKE
2. Build
3. Run main.cpp

## Usage
- arrowkeys or WASD to move camera
- scrollwheel to zoom (origin of zoom bist bottom left corner of the window)


### Credits
Viktor Chlumský:
- https://github.com/Chlumsky/msdfgen
- https://github.com/Chlumsky/msdf-atlas-gen

Michael Martz:
- https://github.com/theOtherMichael/Enterprise
