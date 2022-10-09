# cmkr-qt6-msvc-static-template

https://github.com/build-cpp/cmkr


## Building

```
cmake -Bbuild -DCMAKE_PREFIX_PATH=c:\Qt\6.30\msvc2019_64static -DCMAKE_INSTALL_PREFIX=install -DCMAKE_CONFIGURATION_TYPES="Release"
cmake --build build --config Release
cmake --install build
```
