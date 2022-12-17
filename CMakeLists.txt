cmake_minimum_required(VERSION 3.1)

project(ex_app)

add_executable(ex_app main.cpp)

install(TARGETS ex_app DESTINATION bin)

