cmake_minimum_required(VERSION 3.14)

message(STATUS "===== Starting Root Build =====")

project(CPP_Learning)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Include subdirectories
add_subdirectory(hello_world)