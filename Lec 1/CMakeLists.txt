cmake_minimum_required(VERSION 4.1.1)
set(PROJECT_NAME example)
project("${PROJECT_NAME}")

set(CMAKE_CXX_STANDART 20)

add_executable("{PROJECT_NAME}" main.cpp)
