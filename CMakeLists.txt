cmake_minimum_required(VERSION 3.8)

project(Cpp-Primer)

#add_compile_options(-std=c++11)
# ext1_9 auto is supported on c++14
add_compile_options(-std=c++14)

add_executable(ch01_1 ch01/ex1_1.cpp)
add_executable(ch01_9 ch01/ex1_9.cpp)