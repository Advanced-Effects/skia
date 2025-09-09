# Skia for Friction

Skia fork for use with Friction.

Skia is a complete 2D graphic library for drawing Text, Geometries, and Images.

## Linux

### Requirements

* ninja
* python3
* cmake
* clang
* expat
* freetype
* fontconfig
* libjpeg-turbo
* libpng
* libwebp
* libicu
* zlib

### Build and install

```
mkdir build && cd build
cmake -G Ninja \
-DCMAKE_INSTALL_PREFIX=/usr \
-DCMAKE_CXX_COMPILER=clang++ \
-DCMAKE_C_COMPILER=clang ..
cmake --build .
```

```
cmake --install .
```

This will install `libskia-friction1.so` to defined install path. Add optional `--prefix=/some/path` to install to a different location.
