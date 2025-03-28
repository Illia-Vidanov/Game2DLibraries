cmake_minimum_required(VERSION 3.12)
project(glad)

set(CMAKE_BUILD_TYPE Release)
add_library(glad STATIC ${CMAKE_CURRENT_SOURCE_DIR}/src/glad.c)
target_include_directories(glad PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)