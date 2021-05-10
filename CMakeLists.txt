cmake_minimum_required(VERSION 3.17)
project(GitTest)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(GitTest
        main.cpp
        main.h)
