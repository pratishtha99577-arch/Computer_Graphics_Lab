Computer Graphics Lab – Assignment 1

Basic Geometric Shapes Using C++ and SDL2

Objective

To write a C++ program using the SDL2 graphics library to draw four basic geometric shapes in a single graphics window.

Shapes Implemented

1. Straight Line – Blue
2. Circle – Red (using the Midpoint Circle Algorithm)
3. Rectangle – Green
4. Triangle – Purple

Technologies Used

- C++
- SDL2 Graphics Library
- GCC / MinGW64 Compiler
- Visual Studio Code

Project Structure

CGM-Lab-Assignment-1/
├── BasicShapes.cpp
├── README.md
└── output/
    └── BasicShapes_Output.png

How to Compile

Open the terminal in the assignment folder and run:

& "C:\msys64\mingw64\bin\g++.exe" BasicShapes.cpp -IC:\msys64\mingw64\include\SDL2 -LC:\msys64\mingw64\lib -lmingw32 -lSDL2main -lSDL2 -o BasicShapes.exe

How to Run

$env:Path = "C:\msys64\mingw64\bin;" + $env:Path
.\BasicShapes.exe

Output

See the "output" folder for the screenshot of the program execution.

Learning Outcome

Successfully implemented and displayed four basic geometric shapes using C++ and SDL2, including the Midpoint Circle Algorithm.