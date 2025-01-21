cmake_minimum_required(VERSION 3.5)

project(test-exclusive-lock LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME} main.cpp ../src/exclusive-lock.cpp ../src/exclusive-lock.h)
