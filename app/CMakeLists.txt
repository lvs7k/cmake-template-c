cmake_minimum_required(VERSION 3.0.0)

project(app)

set(
    SOURCES
        main
)

set(
    LIBRARIES
        lib
)

include_directories(${CMAKE_SOURCE_DIR}/src)

add_executable(${PROJECT_NAME} ${SOURCES})

target_link_libraries(${PROJECT_NAME} ${LIBRARIES})