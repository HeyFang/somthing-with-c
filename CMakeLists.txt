cmake_minimum_required(VERSION 3.27)
project(something_with_c)

set(CMAKE_CXX_STANDARD 14)

add_executable(something_with_c
        hello.c
        README.md)
