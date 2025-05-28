cmake_minimum_required(VERSION 3.30)
project(Kursov C)

set(CMAKE_C_STANDARD 23)

add_executable(Kursov main.c
        utils.c
        utils.h
        dictionary.c
        dictionary.h
        io.c
        io.h
        layout.c
        layout.h)
