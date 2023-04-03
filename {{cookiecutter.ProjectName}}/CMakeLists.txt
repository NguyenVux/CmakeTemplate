cmake_minimum_required(VERSION 3.24)
project({{cookiecutter.ProjectName}})
set(CMAKE_CXX_STANDARD 17)

set(LIB_TARGETS)

add_subdirectory(libs)
add_subdirectory(code)