# Build Games in the Browser with C++, Lua & WebAssembly

Course: **Build Games in the Browser with C++, Lua & WebAssembly**\
Platform: **Udemy**

## Course Overview

This course focuses on building browser-based games and a small game
engine using technologies such as:

-   C++
-   WebAssembly (WASM)
-   Emscripten
-   CMake
-   SDL
-   OpenGL
-   GLSL shaders
-   Lua
-   ECS
-   Physics

The course contains approximately **17 sections, 136 lectures, and 39
hours of content**.

------------------------------------------------------------------------

## Course Chapters

  -----------------------------------------------------------------------
  \#                      Chapter / Section       Main Topics
  ----------------------- ----------------------- -----------------------
[x]1                       Introduction            Course overview and
                                                  project introduction

[]2                       Setup                   C++, CMake, Emscripten,
                                                  WebAssembly project
                                                  setup

[]3                       Drawing to the Screen   SDL rendering, Lua,
                                                  Sol2

[]4                       Starting the Jadeite    OpenGL, GLSL shaders,
                          WASM Engine Project     textures, GLM, cameras,
                                                  engine architecture

[]5                       ECS / Components & Lua  EnTT, components, Lua
                          Integration             bindings, runtime
                                                  reflection
[]6                       Rendering Techniques    Batch rendering, VBO,
                                                  VAO, EBO, fonts, text
                                                  rendering

[]7                       Inputs                  Keyboard, mouse and
                                                  gamepad input

[]8                       Cleaning Up Our         Game class and
                           `main.cpp`              application
                                                  architecture
 
[]9                       Sounds and Music        SDL_mixer, music and
                                                  sound effects

[]10                      Helpful Utilities       Asset manager, scripts,
                                                  timers and asset
                                                  reloading

[]11                      Later Game / Engine     Gameplay systems and
                          Development             engine development

[]12                      Game Development        Building gameplay using
                                                  the engine

[]13                      Physics                 Physics concepts and
                                                  integration

[]14                      Box2D                   Box2D physics
                                                  integration

[]15                      Tilemaps                Tile-based world
                                                  rendering

[]16                      Platformer Development  Platformer mechanics
                                                  and systems

[]17                      Completing the Project  Finishing and
                                                  integrating the
                                                  game/engine systems
  -----------------------------------------------------------------------

> **Note:** The exact names of some later Udemy sections may differ.
> This README is intended as a clean learning overview of the course
> structure.

------------------------------------------------------------------------

## Graphics-Focused Chapters

For an **OpenGL / WebGL / GLSL** learning path, the most important parts
of the course are especially:

### Chapter 4 - Jadeite WASM Engine / OpenGL

Topics include:

-   OpenGL initialization
-   Rendering pipeline
-   Vertex shaders
-   Fragment shaders
-   GLSL
-   Shader compilation
-   Shader programs
-   Vertex data
-   Textures
-   GLM mathematics
-   Camera systems
-   Engine architecture

This is one of the most important sections for understanding how C++
code communicates with the GPU.

### Chapter 6 - Rendering Techniques

Topics include:

-   Vertex Buffer Objects (**VBO**)
-   Vertex Array Objects (**VAO**)
-   Element Buffer Objects (**EBO**)
-   Batch rendering
-   Texture batching
-   Font rendering
-   Text rendering
-   Reducing draw calls
-   Organizing rendering code

------------------------------------------------------------------------

## Technology Map

``` text
C++
 |
 +-- CMake
 |
 +-- Emscripten
 |     |
 |     +-- WebAssembly (WASM)
 |
 +-- SDL
 |
 +-- OpenGL
 |     |
 |     +-- GLSL
 |     |    |
 |     |    +-- Vertex Shader
 |     |    +-- Fragment Shader
 |     |
 |     +-- VBO
 |     +-- VAO
 |     +-- EBO
 |     +-- Textures
 |     +-- Camera
 |
 +-- Lua
 |
 +-- ECS
 |
 +-- Box2D
```

------------------------------------------------------------------------

## Suggested Learning Focus

If the main goal is to become stronger in **graphics programming**, pay
particular attention to this progression:

1.  C++ fundamentals
2.  CMake
3.  Emscripten
4.  WebAssembly
5.  SDL basics
6.  OpenGL fundamentals
7.  GLSL
8.  Vertex shaders
9.  Fragment shaders
10. VBO / VAO / EBO
11. Textures
12. Transformations and GLM
13. Cameras
14. Batch rendering
15. Draw-call optimization
16. Game/engine architecture

------------------------------------------------------------------------

## Key Graphics Pipeline

A useful mental model while following the course:

``` text
C++ Application
      |
      v
Vertex Data
      |
      v
VBO
      |
      v
VAO
      |
      v
Vertex Shader
      |
      v
Rasterization
      |
      v
Fragment Shader
      |
      v
Framebuffer
      |
      v
Browser Canvas
```

When compiled for the browser:

``` text
C++
 |
 v
Emscripten
 |
 v
WebAssembly
 |
 v
Browser
 |
 v
WebGL / GPU
```

------------------------------------------------------------------------

## Main Goal

By the end of this learning path, the important goal is not only to
build the example game, but to understand the complete path:

**C++ -\> Emscripten -\> WebAssembly -\> OpenGL/WebGL -\> GLSL -\> GPU**

That foundation can later be extended into:

-   WebGL
-   Three.js
-   WebGPU
-   Native OpenGL
-   C++ graphics engines
-   GPU programming
-   Real-time rendering
-   Shader development
