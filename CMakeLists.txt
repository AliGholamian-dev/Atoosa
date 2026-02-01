cmake_minimum_required(VERSION 3.10)
project(Atoosa C)

add_library(
    Atoosa
    STATIC
    Atoosa.h
    Atoosa.c)
    
target_link_libraries(Atoosa PUBLIC Common)
target_include_directories(Atoosa PUBLIC ${CMAKE_CURRENT_LIST_DIR}/..)
