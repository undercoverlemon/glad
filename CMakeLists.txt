cmake_minimum_required(VERSION 3.31)

project(glad3.3)

add_library(glad3.3 src/glad.c)
target_include_directories(glad3.3 PUBLIC include)