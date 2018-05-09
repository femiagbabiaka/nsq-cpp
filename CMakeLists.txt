cmake_minimum_required(VERSION 3.10)
project(nsq_cpp)

set(CMAKE_CXX_STANDARD 11)

add_library(nsq_cpp library.cpp library.h)