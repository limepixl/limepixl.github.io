---
layout: page
title: Portfolio
permalink: /portfolio/
---

Hello! I'm Stefan Ivanovski (known as limepixl online), a student that is passionate about computer graphics, rendering, and light transport. This blog serves as a future platform to keep my notes, observations, and projects. 

Below you can see a few of the projects I have, and am currently working on.

---  

# **Pathtracer**

![Pathtracer](/assets/pathtracing_journey_1/mis_bvh_blinnphong_bunny.png)

A work-in-progress unidirectional pathtracer implementing light transport techniques, for the purpose of rendering complex scenes with physically-based materials.

Areas of Knowledge:
- Light transport concepts: rendering equation, BRDFs, physically based rendering and path tracing
- Rendering on the GPU with OpenGL compute shaders (OpenGL 4.6 Core)
- Shader optimization via vendor-specific profiler and debugger (NVIDIA Nsight Graphics)
- Cross-platform and cross-compiler C/C++ building with CMake
- Custom Bounding Volume Hierarchy (BVH) creation and traversal

[*(GitHub Link)*](https://github.com/limepixl/pathtracer)

---  

# **3D Model Viewer**

![Model Viewer](https://raw.githubusercontent.com/limepixl/model-viewer/master/img/3.png)

A simple obj model viewer with camera, light and model transform controls.

Areas of Knowledge:
- 3D transformations through usage of model and view matrices
- Usage of OpenGL 3.3 Core for rendering
- Control via parameters in the user interface that control transformations, lights and the model
- Utilization of normal mapping for higher fidelity
- Texture image format caching for performance improvement

[*(GitHub Link)*](https://github.com/limepixl/model-viewer)

---  

# **Chess**

![Chess](https://raw.githubusercontent.com/limepixl/chess/main/renders/render.png)

A fully playable chess game.

Areas of Knowledge:
- User interaction with scene's models using ray picking
- Compilation for general machine architecture, for distribution to university professors
- Custom scene format that defines entities with their meshes and applied transformations

[*(GitHub Link)*](https://github.com/limepixl/chess)