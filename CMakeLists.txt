cmake_minimum_required(VERSION 3.21)
project(10 C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(10
        a1ms2.c
        clinic.c
        clinic.h
        core.c
        core.h)
