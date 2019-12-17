cmake_minimum_required(VERSION 2.8.3)
project(EVALUATION C++)

add_library(Maille src/Maille.cpp)
add_library(Point src/Point.cpp)
add_executable(main src/main2.cpp)

target_link_libraries(main Maille Point)
include_directories(include)
