cmake_minimum_required(VERSION 3.4)
project(aplite)

include_directories(src)
file(GLOB SRC ./src/*.cc)

add_executable(aplite ${SRC})