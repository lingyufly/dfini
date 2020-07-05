cmake_minimum_required(VERSION 3.1)
project(dfxml)

find_package(Boost REQUIRED)
include_directories(${Boost_INCLUDE_DIRS})

include_directories(include)

add_subdirectory(src)
add_subdirectory(test)


