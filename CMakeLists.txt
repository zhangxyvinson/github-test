cmake_minimum_required(VERSION 3.16)
project(github_test LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(main
    src/main.cpp
    src/foo.cpp
)

target_include_directories(main PRIVATE include)