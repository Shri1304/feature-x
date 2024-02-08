cmake_minimum_required(VERSION 3.27)
project(feature_x)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(feature_x
        main.c
        main.h
        README.md)
