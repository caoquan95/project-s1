cmake_minimum_required(VERSION 3.6)
project(project_s1)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Node.cpp Node.h Tree.cpp Tree.h BDD.cpp BDD.h)
add_executable(project_s1 ${SOURCE_FILES})