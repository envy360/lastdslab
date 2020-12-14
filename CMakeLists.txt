cmake_minimum_required(VERSION 3.17)
project(finalLab)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(finalLab
        Graph.cpp
        Graph.h
        main.cpp)
