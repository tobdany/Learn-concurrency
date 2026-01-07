cmake_minimum_required(VERSION 3.10.0)
project(programsapp VERSION 0.1.0 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package(Threads REQUIRED)

add_library(config_concurrencia INTERFACE)
target_compile_options(config_concurrencia INTERFACE -fcoroutines)
target_link_libraries(config_concurrencia INTERFACE Threads::Threads)


add_executable(programsapp holamundo2.cpp)
target_link_libraries(programsapp PRIVATE config_concurrencia)

add_executable(programsapp2 holamundo3.cpp)
target_link_libraries(programsapp2 PRIVATE config_concurrencia)

