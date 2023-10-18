cmake_minimum_required(VERSION 3.26)
project(StacksAndQueues)

set(CMAKE_CXX_STANDARD 17)

add_executable(StacksAndQueues main.cpp
        LinearStruct.cpp
        LinearStruct.h
        Stack.cpp
        Stack.h
        Queue.cpp
        Queue.h)
