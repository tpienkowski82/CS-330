CS 330 3D Scene Project
Overview
This project was created for CS 330 and demonstrates a fully built 3D scene using OpenGL. The scene includes a desk setup with a monitor, keyboard, mouse, and speakers. The goal of the project is to show understanding of core graphics concepts like 3D transformations, texturing, lighting, and camera control.
Scene Description:
The rendered scene represents a desktop workstation and includes:
Monitor
Keyboard
Mouse
Left and right speakers
Objects are built using basic 3D shapes, then positioned and scaled using transformation matrices to form a complete scene.
Features
3D Object Modeling: Scene built from multiple individual objects/shapes
Transformations: Translation, rotation, and scaling used to assemble the workspace
Lighting: Scene lighting configured to create realistic depth and shading
Textures: Textures applied to improve realism (ex: desk surface, screen/background, etc.)
Camera Controls: User can view the scene from different angles using keyboard and/or mouse controls (depending on how your template was set up)
Technologies Used
C++
OpenGL
GLFW
GLAD
GLSL Shaders
How to Run
Download or clone the repository
Open the project in Visual Studio
Build the solution
Run the program
Controls
W A S D: Move camera
Mouse: Look around
Q / E: Move up and down
Scroll Wheel: Zoom in/out
Project Structure
main.cpp — program entry point
SceneManager.* — scene setup, object placement, textures, lighting
ShaderManager.* — shader loading/compiling
ShapeMeshes.* — mesh creation for basic shapes
textures/ — texture image files
What I Learned:
How to build a complete 3D scene by combining multiple shapes and transformations
How lighting and materials impact realism in a rendered environment
How textures are loaded and mapped to objects
How camera movement and perspective affect the final view of a scene

  When I design software now, I’m a lot more intentional than I used to be. For this project, I didn’t just jump into coding and hope it would come together. I started by thinking about the structure first and breaking the work into pieces that made sense, like how I would handle mesh creation, texture loading, lighting, camera setup, and input. That helped me build better design habits because I was thinking about how the whole scene and rendering process works together instead of stuffing everything into one big file. I worked through it in a milestone style, starting with a simple render loop and then adding objects step by step. After that, I added transformations, textures, and lighting, and I tested constantly so I could catch problems early. Once everything was working correctly, I spent time improving the details, like object placement, texture consistency, and lighting, so the scene looked more like a real environment and less like a rough draft. The biggest thing I’ll take from this into future projects is sticking to small, testable steps and keeping the code organized in a way that makes it easier to debug, expand, and maintain.
  My approach to developing programs improved a lot while building the 3D scene too. I leaned heavily on building in small chunks and checking the results on screen as I went, which kept me from getting buried in bugs later. I also got better at writing helper functions and organizing my code, so I wasn’t repeating the same setup work again, especially when working with textures, meshes, and transformations. When something didn’t work, I learned to slow down and troubleshoot in a more logical way instead of randomly changing things. I would check the common trouble spots like file paths, shader compile and link issues, texture binding order, transformation math, and lighting values. Iteration was honestly the whole process, because the scene kept improving in rounds. First, I just needed it to render, then I needed everything placed correctly, then I focused on making it look polished through lighting and textures. Over the milestones, I noticed my mindset changed. At the beginning, it was mostly about getting it to work, but by the end I was thinking more about making it clean, reliable, and easy to explain. I ended up with better naming, fewer hard coded values scattered around, and clearer separation between scene setup, the render loop, and input.
  This project also reminded me of why computer science matters for my bigger goals. Working in computational graphics and visualization forced me to think carefully and solve problems in a way that is both technical and creative. It strengthened my understanding of things like coordinate systems, transformations, and how different parts of a program connect through a pipeline. It also made me more confident learning complex tools and figuring things out when the result on screen is not what I expected. For school, that’s a big deal because it carries into other classes where you must break down a tough requirement, build something step by step, and test your work. For the professional side, the habits matter just as much as the final scene. I practiced working through milestones, handling frustrating bugs in a structured way, and polishing a project until it meets the requirements and looks finished. Even if I do not end up in a graphics focused job, those are the same skills I will need in software development, whether I am building applications, systems, or anything else that requires solid planning, careful testing, and a clean final product.

