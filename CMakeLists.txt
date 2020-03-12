# cmake_minimum_required(VERSION <specify CMake version here>)
project(MM1)

set(CMAKE_CXX_STANDARD 11)

add_executable(MM1 main.cpp Customer.cpp Customer.h EventScheduler.cpp EventScheduler.h Server.cpp Server.h)