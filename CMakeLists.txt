cmake_minimum_required(VERSION 3.7)
project(OOP244_W7_IN_LAB)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Hero.cpp
        Hero.h
        w7_in_lab.cpp)

add_executable(OOP244_W7_IN_LAB ${SOURCE_FILES})