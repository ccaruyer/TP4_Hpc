cmake_minimum_required(VERSION 3.20)
project(TP4)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14 -fopenmp -lgomp")

add_executable(TP4  hpcOpenmpSchedule.cpp)
