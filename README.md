# Kusanagi shader editor

This is a GLSL shader editor written in C++ and using OpenGL. The main purpose of this project is to provide a comfortable and powerful shader editor.
I aim to create an editor that attracts people to use it and, hopefully, we can create a community one day!

Right now, what it is capable of is:

- Create/delete shaders through the UI.
- Add uniforms to your shaders through the UI.
- Save everything.
- Add more framebuffers to your shader. It will automatically pass the output texture of the previous frame buffer to the next one.
- Load images as uniforms.
- A console for debugging the code.

I am currently implementing the "community" part of it! Database, S3 to upload/download the shaders, etc. 

Here you can see some screenshots:

![Shader_1](https://user-images.githubusercontent.com/107591581/173961888-8595a8cc-b134-4a5e-89f5-be8405e5a982.png)
---
![Shader_2](https://user-images.githubusercontent.com/107591581/173961893-d90b790d-d25a-417f-8d1a-5893967bdd05.png)
---
![Shader_5](https://user-images.githubusercontent.com/107591581/173961886-87c0c949-b2f4-4e21-8c81-193863051101.png)
---
![Shader_3](https://user-images.githubusercontent.com/107591581/173961882-305f1b5f-6e71-4c15-b7b6-d2c63bdfe88a.png)

## Tasks currently under development

- User registration and login
- Import shaders from shadertoy to the Kusanagi Shader Editor by pasting a link
- Shader registry:
  - Upload shaders to the registry
  - Download shaders from the registry
  - UI for navigating the uploaded shaders
- Import cubemaps
