cmake_minimum_required (VERSION 2.6)

#include_directories ("./include")

add_definitions(-DDEBUG)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -ggdb")
set(LIBRARY_OUTPUT_PATH ./lib)

add_library(unity STATIC src/unity.c)
