cmake_minimum_required(VERSION 3.1)
project(test)
set(SRC main.cpp)
add_executable(test ${SRC})

target_link_libraries(test dfxml)


