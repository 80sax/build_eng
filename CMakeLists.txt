cmake_minimum_required(VERSION 3.15)
project(SortArrayProject LANGUAGES C CXX)

enable_testing()

# Global settings
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

include_directories(include)

add_subdirectory(src)
add_subdirectory(tests)
add_subdirectory(sort_array)