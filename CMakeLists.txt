cmake_minimum_required(VERSION 4.0.2)

set(PROJECT_NAME laPSolver)

project(${PROJECT_NAME})

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS_DEBUG "-g -Wall")
set(CMAKE_CXX_REQUIRED True)

# Find Eigen
find_package(Eigen3 3.4 REQUIRED NO_MODULE)

include_directories(include)

file(GLOB SOURCES "./src/*.cpp" "./*.hpp")

add_executable(${PROJECT_NAME} ${SOURCES})
