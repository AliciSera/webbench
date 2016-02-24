cmake_minimum_required(VERSION 2.8)

project(webbench)

aux_source_directory(. SRC)

add_executable(webbench ${SRC})

install(TARGETS webbench DESTINATION bin)