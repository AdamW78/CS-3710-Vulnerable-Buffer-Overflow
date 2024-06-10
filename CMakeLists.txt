cmake_minimum_required(VERSION 3.29)
project(Vulnerable C)

set(CMAKE_C_STANDARD 23)

add_executable(Vulnerable overflow.c)
