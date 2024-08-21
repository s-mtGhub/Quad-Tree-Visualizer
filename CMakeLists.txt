cmake_minimum_required(VERSION 3.27)
project(QuadTree_visualizer)

set(CMAKE_CXX_STANDARD 14)

include_directories(quadtree-visualization)

add_executable(QuadTree_visualizer
        quadtree-visualization/quad-x-gl.cpp
        quadtree-visualization/quadtree.cpp
        quadtree-visualization/quadtree.h)
