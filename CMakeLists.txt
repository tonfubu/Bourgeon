cmake_minimum_required(VERSION 2.8)

project(Bourgeon CXX)

add_definitions(-DBOURGEON_VERSION="0.1")
add_definitions(-DWITH_THREAD)

add_subdirectory(src)
add_subdirectory(thirdparty)
