cmake_minimum_required(VERSION 3.2 FATAL_ERROR)
project(game)

add_executable(game main.cpp)

target_link_libraries(game SDL2-static)