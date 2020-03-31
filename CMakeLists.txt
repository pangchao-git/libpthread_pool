cmake_minimum_required(VERSION 3.15)
project(Test_threadpool)

set(CMAKE_CXX_STANDARD 14)

add_executable(Test_threadpool main.cpp threadpool.h)
target_link_libraries(Test_threadpool pthread)