cmake_minimum_required(VERSION 2.8)
project(hello)
enable_testing()
add_executable(hello main.cpp)
add_test(zero hello)

