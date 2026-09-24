cmake_minimum_required(VERSION 2.8.3)
project(mini_core)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "-Wall -Wextra -pedantic")


find_package(Eigen3 REQUIRED)

add_subdirectory(src)

add_subdirectory(executables)
