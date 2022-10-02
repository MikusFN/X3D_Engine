cmake_minimum_required(VERSION 3.16.2)

project(X3D_Engine)

# OPTIONS -------------------------------------------------------------
option(ENABLE_X64_ARCH "Enable x64 compilation" ${ENABLE_X64_ARCH})

#----------------------------------------------------------------------
set(ROOT_DIRECTORY ${CMAKE_CURRENT_LIST_DIR})


# Project Executable
add_executable(${PROJECT_NAME} source/main.cpp)
