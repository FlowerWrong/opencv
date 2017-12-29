cmake_minimum_required(VERSION 3.8)
project(cv)

find_package(OpenCV REQUIRED)

add_executable(cv src/main.cpp)
target_link_libraries(cv ${OpenCV_LIBS})
