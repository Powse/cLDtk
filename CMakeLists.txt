cmake_minimum_required(VERSION 3.21)
project(cLDtk LANGUAGES C)

set(CMAKE_C_STANDARD 99)

file(GLOB SOURCES "*.c")
add_library(${PROJECT_NAME} ${SOURCES})