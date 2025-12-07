# Ray Tracing in C++

## 🚀 Overview

This project implements a basic ray tracer in C++. The goal is to explore and practice core computer-graphics and object-oriented programming concepts: sending rays through a virtual scene, detecting intersections with geometric objects, computing lighting (diffuse, specular, shadows, reflections), and producing rendered images.  
It’s a self-contained renderer — no heavy external graphics APIs required — making it ideal for learning, experimentation, and extensions.

## Features

- Ray–object intersection (e.g., spheres, planes, meshes)  
- Illumination model with support for:  
  - Diffuse lighting  
  - Specular highlights & reflections  
  - Shadow rays for occlusion / light visibility  
- Configurable camera and viewport (field of view, aspect ratio, image resolution)  
- Basic scene description (hard-coded or via simple scene files — adapt as needed)  
- Image output (e.g., PNG, BMP — depending on your implementation)  
- Modular, object-oriented C++ code structure for easy extension / experimentation  


## Getting Started

### Prerequisites

- A C++ compiler (e.g., `g++`, `clang++`, or MSVC) supporting C++17 or later  
- (Optional) Build tool like `cmake` or a simple Makefile, depending on your setup  
- Basic linear algebra support (vector, point, ray classes) — included in the repo  

### Build & Run

```bash
# Example (assuming a basic Makefile or CMake setup):
mkdir build
cd build
cmake ..         # or use your build tool / Makefile
make
./raytracer      # or appropriate executable name
# Optionally supply scene file(s) or parameters
