cmake_minimum_required(VERSION 3.25)
project(Arch)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_subdirectory(./src/cli)

add_subdirectory(./example)
