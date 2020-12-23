cmake_minimum_required(VERSION 3.17)
project(write_a_C_interpreter C)

set(CMAKE_C_STANDARD 11)

add_executable(write_a_C_interpreter
        xc.c)