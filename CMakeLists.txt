cmake_minimum_required(VERSION 3.16)
project(game_box_coding_challenge VERSION 1.0.0 LANGUAGES CXX )

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(EXECUTABLE_NAME challenge)

add_executable(${EXECUTABLE_NAME} asaphus_coding_challenge.cpp)

target_link_libraries(${EXECUTABLE_NAME})
