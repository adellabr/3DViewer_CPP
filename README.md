# 3DViewer_CPP
Application for viewing 3D wireframe models in C++

## General Information about the Program

This program provides the capability to view a 3D model in wireframe mode. The models are stored in files of the .obj format.

## Program Description

- The program is developed in C++ using the C++17 standard.
- The program's build is configured using a Makefile with the standard set of targets for GNU programs: all, install, uninstall, clean, dvi, dist, tests.
- The program is developed according to the principles of object-oriented programming.
- Full coverage with unit tests has been ensured for modules related to model loading and affine transformations.
- The program provides the ability to:
    - Load a wireframe model from an .obj file (supporting only vertex and surface lists);
    - Move the model by a specified distance along the X, Y, Z axes;
    - Rotate the model by a specified angle around its X, Y, Z axes;
    - Scale the model by a specified value.
- The program features a graphical user interface based on Qt.

**The graphical user interface includes:**

    - A button to select a file with the model and a field to display its name;
    - A visualization area for the wireframe model;
    - A slider for moving the model;
    - A slider for rotating the model;
    - A slider for scaling the model;
    - Information about the loaded model — file name, number of vertices, and edges.

- The program is implemented using the MVC pattern.
- Three different design patterns are used (strategy, bridge, mediator).
