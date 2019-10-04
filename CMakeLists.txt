cmake_minimum_required(VERSION 2.8)
project(cmake)


# enable c++11 support
set (CMAKE_CXX_FLAGS "-std=c++11 -Wall ${CMAKE_CXX_FLAGS}")

# create the main executable
add_executable(
cmake
hello.cpp)

# add_executable(tests file_name.cpp)
