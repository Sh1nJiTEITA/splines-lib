cmake_minimum_required(VERSION 3.10)
project(splines-lib)

add_library(splines-lib STATIC ${CMAKE_CURRENT_SOURCE_DIR}/Splines.cpp)

target_include_directories(splines-lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
