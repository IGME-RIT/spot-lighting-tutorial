# Point Lighting Tutorial

This program demonstrates an implementation for point lighting in a scene.

# About

Takes the Standard3D project from Basic Shape Rendering and adds in a point light. This involves adding a normal to each vertex (and thus, binding the normal and passing it into the Vertex Shader), modifying the normal by the world/model/transformation matrix, then passing it into the Fragment Shader and performing the calculations necessary. The diffuseColor, lightPosition, ambientCoefficient, and attenuation values are hard-coded into the Fragment Shader, but could easily be extracted as variables passed in so that they could be dynamically modified. This project introduces the concepts of ambient lighting, attenuation, and gamma correction.

# Setup

In order to setup, run the following in a shell, then open the project in your preferred editor. Windows setup has been configured for use with Visual Studio.

Windows:
```
cd path/to/folder
setup.cmd
```
Linux:
```
cd path/to/folder
./setup
```

# Credits

Sample references http://www.tomdalling.com/blog/modern-opengl/08-even-more-lighting-directional-lights-spotlights-multiple-lights/.
