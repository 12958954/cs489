cmake_minimum_required(VERSION 3.22.1)
project (work)
set(CMAKE_CXX_STANDARD 11)

include_directories(include)
add_executable(work input.c job.c main.c)
