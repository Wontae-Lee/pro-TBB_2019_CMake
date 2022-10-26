# CMake version
cmake_minimum_required(VERSION 3.22.1)

# Project name
project(TBB_tutorial)

# CPP version
set(CMAKE_CXX_STANDARD 17)

# Look for TBB
include(FindTBB.cmake)

# Include headers
include_directories(external)
include_directories(external/oneDPL/include)

#---------
# Modules
# --------

# oneAPI
add_subdirectory(./external/oneDPL)

# AppB
add_subdirectory(./AppB)

# Chapters
add_subdirectory(./ch07)
add_subdirectory(./ch15)
add_subdirectory(./ch05)
add_subdirectory(./ch17)
add_subdirectory(./ch04)
add_subdirectory(./ch01)
add_subdirectory(./ch19)
add_subdirectory(./ch19/TriadOpenCLNode)
add_subdirectory(./ch19/HelloOpenCLNode)
add_subdirectory(./ch11)
add_subdirectory(./ch03)
add_subdirectory(./ch13)
add_subdirectory(./ch20)
add_subdirectory(./ch02)
add_subdirectory(./ch12)
add_subdirectory(./ch10)
add_subdirectory(./ch14)
add_subdirectory(./ch16)
add_subdirectory(./ch18)
add_subdirectory(./ch06)
