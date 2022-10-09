# cmkr-qt6-msvc-static-template

https://github.com/gmh5225/static-build-qt6/releases/download/qt6_630_static/qt6_630_static_64.zip

https://github.com/build-cpp/cmkr

https://github.com/build-cpp/Qt5CMakeTemplate

## Building

```
cmake -Bbuild -DCMAKE_PREFIX_PATH=c:\Qt\6.30\msvc2019_64static -DCMAKE_INSTALL_PREFIX=install -DCMAKE_CONFIGURATION_TYPES="Release"
cmake --build build --config Release
cmake --install build
```
