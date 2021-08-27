cmake_minimum_required(VERSION 3.20.0)

project (snake-game)

add_executable(a main.cpp)

enable_testing()

add_test(test a)