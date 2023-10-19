cmake_minimum_required(VERSION 3.2)

project(demo)

add_executable(${PROJECT_NAME} main.cpp)

install(TARGETS ${PROJECT_NAME} DESTINATION bin)