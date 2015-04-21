cmake_minimum_required(VERSION 3.1)
project(robust_io)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.c)
add_executable(robust_io ${SOURCE_FILES} rio.h)