cmake_minimum_required(VERSION 2.8)
project(cmake_wrapper)

set(CMAKE_VERBOSE_MAKEFILE ON)

include(conanbuildinfo.cmake)
conan_basic_setup()

add_subdirectory("source_subfolder")
