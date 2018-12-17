#CMAKE Configuration for Project CPP-GRPC
cmake_minimum_required (VERSION 3.0)
project (CPP-GRPC)

set (Tutorial_VERSION_MAJOR 1)
set (Tutorial_VERSION_MINOR 0)

include_directories("${PROJECT_BINARY_DIR}/include")
add_executable(main src/main.cpp)
