cmake_minimum_required(VERSION 3.10)
project(Task_3)

set(CMAKE_CXX_STANDARD 17)

# sani flags
set(SANITIZER_FLAGS "-fsanitize=address -fsanitize=undefined -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} ${SANITIZER_FLAGS}")

# add exec file
add_executable(Task_3 Task_3.cpp)