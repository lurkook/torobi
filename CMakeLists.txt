cmake_minimum_required(VERSION 3.5)
project(TOROBI)

include_directories(include)

file(GLOB_RECURSE SOURCES src/main.c)
add_executable(torobi ${SOURCES})