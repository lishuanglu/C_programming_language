cmake_minimum_required(VERSION 3.17)
project(C_programming_language C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(chapter1_Introduction)

add_executable(C_programming_language
        chapter1_Introduction/1-1.c)

add_executable(1-1 chapter1_Introduction/1-1.c)