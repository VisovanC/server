cmake_minimum_required(VERSION 3.24)
project(cnsvbun)

set(CMAKE_CXX_STANDARD 17)

add_executable(cnsvbun main.cpp)

target_link_libraries(cnsvbun wsock32 ws2_32 -static)