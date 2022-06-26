cmake_minimum_required(VERSION 3.22)
project(libc C)

set(CMAKE_C_STANDARD 99)

if (${CMAKE_SOURCE_DIR} STREQUAL ${CMAKE_CURRENT_SOURCE_DIR})
    add_subdirectory(test)
endif ()