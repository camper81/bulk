cmake_minimum_required(VERSION 3.8)

project(bulk)

add_executable(bulk main.cpp)

target_compile_features(bulk PRIVATE cxx_std_20)