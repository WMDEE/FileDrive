cmake_minimum_required(VERSION 3.20)
project(Backend)

set(CMAKE_CXX_STANDARD 14)
set(OpenGlLinkers -lglut -lGLU -lGL) # setting all the Glut libraries as one variable.

add_executable(Backend main.cpp)
target_link_libraries(Backend ${OpenGlLinkers}) # linking opengl libraries to the project