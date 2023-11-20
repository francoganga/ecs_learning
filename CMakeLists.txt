cmake_minimum_required(VERSION 3.15)
project(example
  LANGUAGES CXX
  VERSION 1.0
)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
add_subdirectory(dependencies)
add_subdirectory(src)
