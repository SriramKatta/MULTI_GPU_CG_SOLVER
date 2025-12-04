cmake_minimum_required(VERSION 3.10.0)
project(multi_gu_cg VERSION 0.1.0 LANGUAGES C CXX)

include(cmake/CPM.cmake)
include(cmake/FMT.cmake)

set(EXE_NAME ${PROJECT_NAME})

add_executable(${EXE_NAME} main.cpp)

