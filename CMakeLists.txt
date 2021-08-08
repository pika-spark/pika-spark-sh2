cmake_minimum_required(VERSION 3.13.1)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

project(sh2)

add_library(sh2
    sh2_util.c
    shtp.c
    sh2_SensorValue.c
    sh2.c)
target_include_directories(sh2 INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
