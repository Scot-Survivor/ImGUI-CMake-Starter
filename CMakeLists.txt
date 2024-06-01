cmake_minimum_required(VERSION 3.27)
project(Better_PSO)

set(CMAKE_CXX_STANDARD 17)

add_executable(${PROJECT_NAME} main.cpp)

# Add third party libraries.
add_subdirectory(libs)
target_include_directories(${PROJECT_NAME} PUBLIC include)
