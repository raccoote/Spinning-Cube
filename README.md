This C code is a simple OpenGL program that creates a rotating and scaling cube. The program uses the GLUT library for window management and rendering. It begins by defining several global variables, including parameters for the cube's size, rotation angle, and step sizes for animation. The cube is rendered with different colors on each face.

The MyInit function initializes the OpenGL environment, setting the clear color, enabling depth testing, and defining the orthographic projection. The cube's geometry is precompiled into a display list for efficiency.

The createGLUTMenus function sets up a simple menu with two options for different cube viewing modes and an exit option. The menu function is called when a menu item is selected, updating the menuID variable accordingly.

The Spin function handles the cube's animation, adjusting the rotation angle and cube size over time. The DrawCube function defines the cube's six faces with different colors, and the Draw function renders the cube based on the current viewing mode.

In the main function, the program initializes GLUT, creates a window, and sets up the rendering and animation functions. The menu is also created, and the program enters the GLUT main loop for window management and event handling. The cube rotates and scales continuously, providing a visual demonstration of simple OpenGL rendering and animation techniques.


![image](https://github.com/raccoote/Spinning-Cube/assets/74006924/0a322301-d19a-4504-b960-2f5be05b32e0)


![image](https://github.com/raccoote/Spinning-Cube/assets/74006924/9e08a918-5c56-4820-b0a0-59b24c83e91f)



