cmake_minimum_required(VERSION 3.22.1 FATAL_ERROR)
  project(formatter_lib) 
  set(CMAKE_CXX_STANDARD 11)
  set(CMAKE_CXX_STANDARD_REQUIRED ON)
  add_library(formatter_lib STATIC ${CMAKE_CURRENT_SOURCE_DIR}/src/formatter.cpp)
