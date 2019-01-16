cmake_minimum_required(VERSION 3.0.0)

project(lib)

set(
    SOURCES
        lib
)

add_library(${PROJECT_NAME} ${SOURCES})