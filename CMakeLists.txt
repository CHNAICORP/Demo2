cmake_minimum_required(VERSION 3.22)
project(Demo2 C)

set(CMAKE_C_STANDARD 11)

add_subdirectory(TestC)
add_executable(Demo2 main.c TestC/file1.c TestC/file2.c TestC/file3.c)
