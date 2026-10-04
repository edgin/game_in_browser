cmake_minimum_required(VERSION 3.20)
project(em_cmake_test)

set(cmake_CXX_STANDARD 20)

add_executable(
  em_cmake_test
  main.cpp
)

set(CMAKE_CXX_STANDARD "${CMAKE_CXX_FLAGS} -03")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++20")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_EXECUTABLE_SUFFIX ".html")
