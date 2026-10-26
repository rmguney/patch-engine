# Patch (legacy)

> **Archived.** This branch holds the earlier prototype of Patch, kept for reference. Active development is on [`main`](https://github.com/rmguney/patch-engine/tree/main).

Rasterized voxel prototype with three sample scenes: ball pit, melee and shooter. Simulation is C11; the Vulkan renderer is C++20.

![ball pit](.github/readme/ballpit.gif)
![melee](.github/readme/melee.gif)
![shooter](.github/readme/shooter.gif)

## Build (Windows)

Requires CMake 3.21+, MSVC or clang-cl, and the Vulkan SDK (for the headers, loader and `glslc`).

```shell
git clone -b legacy https://github.com/rmguney/patch-engine
cd patch-engine
cmake -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build --config Release
```

## License

[GPL-3.0](LICENSE)
