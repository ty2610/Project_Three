cmake_minimum_required(VERSION 3.8)
project(Project_Three)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(Project_Three ${SOURCE_FILES})

find_package( Threads REQUIRED )
target_link_libraries( Project_Three Threads::Threads )