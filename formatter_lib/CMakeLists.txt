cmake_minimum_required(VERSION 3.10)

project(formatter_lib)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(formatter_lib STATIC formatter.cpp formatter.h)

target_include_directories(formatter_lib PUBLIC
  ${CMAKE_CURRENT_SOURCE_DIR}
)
