cmake_minimum_required(VERSION 3.14)

message(STATUS "===== Starting hello_world Build=====")

# Name of the project
project(hello_world)

# This is the name of the Exe change this and it will change everywhere
set(TargetName HelloWorld)

# use C++ 23
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS ON)

# Make it easy to specify many files
set(SOURCES hello_world.cpp)

# Set the name of the executable we want to build
add_executable(${TargetName} ${SOURCES})

# Link the executable to the standard C++ library
target_link_libraries(HelloWorld stdc++)