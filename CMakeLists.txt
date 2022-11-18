cmake_minimum_required(VERSION 3.22)
project(shell_projet C)

set(CMAKE_C_STANDARD 99)

add_executable(shell_projet main.c shell.h prompt.c source.h source.c scanner.h scanner.c parser.h parser.c node.h node.c executor.h executor.c)
