cmake_minimum_required(VERSION 3.0)
project(Testing)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Werror")

add_executable(Testing main.cpp)
