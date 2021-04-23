cmake_minimum_required(VERSION 3.12 FATAL_ERROR)

project(cpp_basics_demo)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# исполняемый файл из исходного кода
add_executable(main main.cpp)
