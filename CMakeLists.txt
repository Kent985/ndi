cmake_minimum_required(VERSION 2.6)
project(NDI C) 

#set(CMAKE_VERBOSE_MAKEFILE ON)
set(CMAKE_C_FLAGS "-std=c99 -g -Wall")

# add_library(c)  # crée un lib 
add_executable(ndi ndi.c ) 
target_link_libraries(ndi m ) # nom de file.exe  -lib 

test;