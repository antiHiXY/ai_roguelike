Learning materials for the course "AI for videogames" based on simple roguelike mechanics.
* w1 - FSM

## Dependencies
This project uses:
* bgfx for week1 project
* flecs for ECS

## Building

To build you first need to update submodules:
```
git submodule sync
git submodule update --init --recursive
```

Then you need to build using cmake:
```
cmake .
cmake --build .
```