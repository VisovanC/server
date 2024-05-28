cmake_minimum_required(VERSION 3.24)
project(cnclient3)

set(CMAKE_CXX_STANDARD 17)

add_executable(cnclient3 main.cpp)

target_link_libraries(cnclient3 wsock32 ws2_32 -static)