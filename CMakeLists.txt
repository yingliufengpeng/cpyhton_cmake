cmake_minimum_required(VERSION 3.10)
project(cpyhton_cmake)

set(CMAKE_C_STANDARD 99)

include_directories(include)

include_directories(Object)

set(SOURCE_FILES main.c)
add_executable(cpyhton_cmake ${SOURCE_FILES})