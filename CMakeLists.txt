cmake_minimum_required(VERSION 2.8)

project(Templates)
SET(SRC_DIR src)
file(GLOB ALL_SOURCES
    "${SRC_DIR}/*.h"
    "${SRC_DIR}/*.cpp"
)
add_executable(${PROJECT_NAME} ${ALL_SOURCES})
