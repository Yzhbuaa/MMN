# cmake_minimum_required(VERSION <specify CMake version here>)
project(Queue_MMN)

set(CMAKE_CXX_STANDARD 11)

add_executable(Queue_MMN main.cpp Customer.cpp Customer.h EventScheduler.cpp EventScheduler.h Server.cpp Server.h)