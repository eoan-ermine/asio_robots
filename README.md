# asio_robots

Do you want to control robots? Use Boost.Asio!

## Build

```shell
mkdir build && cd build
conan install .. -of .
cmake --preset conan-release .
cmake --build build
```
