CS 330 3D Scene Project
Overview

This project was created for CS 330 and demonstrates a fully built 3D scene using OpenGL. The scene includes a desk setup with a monitor, keyboard, mouse, and speakers. The goal of the project is to show understanding of core graphics concepts like 3D transformations, texturing, lighting, and camera control.

Scene Description

The rendered scene represents a desktop workstation and includes:

Monitor

Keyboard

Mouse

Left and right speakers (with circular speaker details)

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

Open the project in Visual Studio (or your IDE)

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

What I Learned

How to build a complete 3D scene by combining multiple shapes and transformations

How lighting and materials impact realism in a rendered environment

How textures are loaded and mapped to objects

How camera movement and perspective affect the final view of a scene
