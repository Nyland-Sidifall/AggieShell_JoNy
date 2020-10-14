cmake_minimum_required(VERSION 3.14)
project(AggieShell_JoNy)

set(CMAKE_C_STANDARD 99)
add_library(-lreadline)
add_executable(AggieShell_JoNy shell.c)