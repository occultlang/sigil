cmake_minimum_required(VERSION 3.5)

project(sigil)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++23 -Wall -Wextra")

add_library(sigil SHARED src/main.cpp)
set_target_properties(sigil PROPERTIES PREFIX "")
