project(gtest CXX C)
cmake_minimum_required(VERSION 2.6.2)

include_directories(include)

add_library(gtest src/gtest-all.cc)

add_library(gtest_main src/gtest_main.cc)
