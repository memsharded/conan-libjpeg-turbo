PROJECT(conanzlib)
cmake_minimum_required(VERSION 2.8)
include(conanbuildinfo.cmake)
CONAN_BASIC_SETUP()
add_subdirectory("./zlib-1.2.8")