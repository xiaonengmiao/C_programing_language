cmake_minimum_required(VERSION 3.6)
project(C_programing_language)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Chapter1/ex1-1.cpp)
add_executable(C_programing_language ${SOURCE_FILES})