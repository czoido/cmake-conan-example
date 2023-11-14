cmake_minimum_required(VERSION 3.25)
project(ascii_image)

set(CMAKE_CXX_STANDARD 17)

find_package(CURL)

add_executable(ascii_image main.cpp)

target_link_libraries(ascii_image CURL::libcurl)
