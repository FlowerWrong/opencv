cmake_minimum_required(VERSION 3.0)
project(cv)

find_package(OpenCV REQUIRED)

message(STATUS "OpenCV library status:")
message(STATUS "    version: ${OpenCV_VERSION}")
message(STATUS "    libraries: ${OpenCV_LIBS}")
message(STATUS "    include path: ${OpenCV_INCLUDE_DIRS}")

add_executable(cv src/main.cpp)
target_link_libraries(cv ${OpenCV_LIBS})
