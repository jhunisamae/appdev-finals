cmake_minimum_required(VERSION 3.10)

project(appdev-finals)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_TRY_COMPILE_CONFIGURATION "-D_ADI_COMPILER;__VERSIONNUM__")

set(SOURCES
    hello.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})
