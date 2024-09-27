cmake_minimum_required(VERSION 3.15)

project(LochNES VERSION 1.0
                DESCRIPTION "A simple NES emulator in C++"
                LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)

add_executable(${PROJECT_NAME} src/Main.cpp)
target_include_directories(${PROJECT_NAME} PUBLIC include)