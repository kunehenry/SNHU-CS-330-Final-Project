# CS 330 Computational Graphics and Visualization

## Project Overview

This repository contains my portfolio artifacts for CS 330: Computational Graphics and Visualization. The final project is a 3D kitchen coffee scene created with C++ and OpenGL. The scene recreates a kitchen counter arrangement with a coffee maker, ceramic mug, orange, wooden tray, marble countertop, and tiled backsplash.

The goal of the project was to demonstrate the full 3D graphics development process, including object construction, transformation, texturing, lighting, camera movement, and iterative refinement. I built the scene from reusable low-polygon primitives and used textures, materials, and lighting to make the objects recognizable and visually realistic.

## Repository Contents

- `CS-330 Module 7 Final Project - 3D Scene.zip` - Final 3D scene project files
- `CS-330 Module 7 Final Project - Design Decisions.docx` - Design decisions and project explanation
- `README.md` - Portfolio reflection

## Project Features

- 3D object modeling using boxes, cylinders, tapered cylinders, spheres, and torus meshes
- Transformations using scaling, rotation, and translation
- Texture mapping for surfaces such as wood, marble, tile, orange peel, ceramic, plastic, metal, and glass
- Material settings using ambient, diffuse, specular, and shininess values
- Phong-style lighting with multiple point lights and attenuation
- Interactive camera movement using keyboard, mouse, scroll wheel, and projection mode switching
- Modular rendering functions for maintainable scene organization

## Reflection

### How do I approach designing software?

I approach software design by first breaking the problem into smaller pieces that can be understood and built one at a time. For this project, I started with the reference image and identified the main objects in the scene: the coffee maker, mug, orange, wooden tray, countertop, and backsplash. From there, I planned which basic 3D shapes could represent each object while still keeping the scene realistic and manageable.

This project helped me improve my ability to translate real-world objects into simpler geometric forms. I learned how to think about an object in layers: its overall shape, its smaller details, its material, and how it should react to light. I also became more comfortable designing with reusability in mind. Instead of treating every object as a completely separate problem, I used reusable primitives, reusable material settings, and helper functions for transformations, textures, and shader values.

My design process was iterative. I created the base scene first, then added more complex details such as the mug handle, carafe, coffee volume, tray sides, backsplash, and material differences. After each addition, I checked whether the proportions and placement still matched the reference scene. This design approach can be applied in future work because most software projects benefit from decomposition, planning, reusable components, and repeated refinement.

### How do I approach developing programs?

I approach development by building a working version first and then improving it through testing and revision. While working on my 3D scene, I used several new development strategies, including modular rendering functions, parameterized transformations, texture tagging, material definitions, and organized scene setup. I separated preparation tasks, such as loading textures and setting lights, from rendering tasks that draw each object.

Iteration played a major role in completing the project. Early versions of the scene had proportion and lighting issues. For example, the mug and orange were too large compared to the coffee maker, so I adjusted their scale and placement. The countertop and backsplash also became too bright under the first lighting setup, so I reduced the light intensity, adjusted specular values, added attenuation, and used tone mapping to preserve texture detail. I also revised the carafe and coffee surface so that the liquid looked more natural inside the glass.

My approach to development evolved across the milestones. At the beginning of the course, I focused mostly on placing basic shapes in the scene. As the project progressed, I started thinking more about code organization, user interaction, visual realism, and maintainability. By the final version, I was not just drawing objects; I was managing a complete scene with camera controls, textures, lighting, materials, and reusable functions. This helped me understand that good development is not only about making code run, but also about making it clear, adaptable, and easier to revise.

### How can computer science help me in reaching my goals?

Computer science helps me reach my goals by giving me the ability to solve problems logically and build complete systems from smaller parts. This course showed me how computational graphics and visualization connect programming, mathematics, design, and user interaction. I gained practical experience with 3D coordinate systems, transformations, textures, shaders, lighting, camera movement, and rendering.

In my future educational pathway, these skills will help me in advanced programming, graphics, simulation, game development, user interface design, and data visualization. Understanding how 3D scenes are built also strengthens my general problem-solving skills because it requires planning, debugging, testing, and improving a system visually and technically.

In my future professional pathway, computational graphics and visualization can help me build software that communicates information clearly and interactively. The same skills used in this project can apply to fields such as software development, game development, virtual reality, simulation, training tools, product visualization, and interactive applications. Even outside of graphics-specific roles, this project helped me practice writing modular code, managing complexity, and improving a program through iteration, which are important skills for any software development career.
