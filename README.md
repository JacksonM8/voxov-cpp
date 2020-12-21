# voxov-cpp
A personal learning project to help refresh my memory of how raycasting and sparse voxel octrees might be used in a graphics engine

## Goals
- Refresh raycasting/SVO concepts
- Explore cross platform C++/CMake projkect development from a blank slate
- Should be simple and easy for third party who stumbles across the project to build and run it
- Concentrate on producing a recognisably functional end result in a short timeframe

## Scope/Constraints
- Project will use modern CMake (FetchContent where possible)
- Project will target C++17 (potentially C++20 should that become a worthwhile consideration down the track)
- Project should aim to use cross-platform compatible frameworks, and should generate, build and run on:
  - Windows
  - MacOS
  - Linux (Ubuntu for the sake of picking something)
- Aim to be able to render a model by around Christmas day
