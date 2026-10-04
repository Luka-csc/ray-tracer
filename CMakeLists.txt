cmake_minimum_required(VERSION 3.20)
project(ray_tracer CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(ray_tracer src/main.cpp)
target_link_options(ray_tracer PRIVATE -static)