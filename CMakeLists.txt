cmake_minimum_required(VERSION 3.24)
project(matrixx C)

set(CMAKE_C_STANDARD 99)

add_executable(matrixx main.c matrix.c matrix.h)
