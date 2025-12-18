# CS 330 3D Scene Project (OpenGL)

This project was created for **CS 330** and demonstrates a fully built 3D scene using **OpenGL**. The scene is designed to showcase core graphics programming concepts including **3D transformations**, **texturing**, **lighting**, and **camera controls**.

## Scene Overview
The rendered scene represents a desktop workstation and includes:
- Monitor
- Keyboard
- Mouse
- Left and right speakers

All objects are constructed from basic 3D shapes, positioned and scaled using transformation matrices to form a complete workspace.

## Key Features
- **3D Object Modeling:** Scene built from multiple individual objects/shapes  
- **Transformations:** Translation, rotation, and scaling to assemble the scene  
- **Lighting:** Configured to create realistic depth and shading  
- **Textures:** Applied to improve realism (desk surface, screen/background, etc.)  
- **Camera Controls:** Navigate and view the scene from multiple angles

## Controls
- **W / A / S / D:** Move camera
- **Mouse:** Look around
- **Q / E:** Move up / down
- **Scroll Wheel:** Zoom in / out

## Technologies Used
- **Language:** C++
- **Graphics:** OpenGL
- **Window/Input:** GLFW
- **OpenGL Loading:** GLAD
- **Shaders:** GLSL

## How to Run
1. Download or clone the repository.
2. Open the project in **Visual Studio**.
3. Build the solution.
4. Run the program.

## Project Structure
- `main.cpp` — Program entry point  
- `SceneManager.*` — Scene setup, object placement, textures, lighting  
- `ShaderManager.*` — Shader loading/compiling  
- `ShapeMeshes.*` — Mesh creation for basic shapes  
- `assets/` (or equivalent) — Texture images and other resources

## Reflection / What I Learned
This project helped me understand how to build a complete 3D scene by combining multiple shapes, transformations, materials, textures, lighting, and camera input into a clean render pipeline. I also improved my workflow by building in small milestones, testing frequently, and keeping code organized with helper functions and clear separation between scene setup, rendering, and input. Overall, it strengthened both my technical skills (coordinate systems, transformations, shaders) and my ability to troubleshoot issues logically while polishing a final product.

## Future Improvements
- Add more detailed materials/lighting variations
- Improve texture consistency across objects
- Add UI toggles for lighting/camera settings
