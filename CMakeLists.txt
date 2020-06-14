cmake_minimum_required(VERSION 3.15)

project(stb_image CXX)

add_library(stb_image STATIC
    stb_image.h
)

target_include_directories(stb_image PUBLIC)
set_target_properties(stb_image PROPERTIES LINKER_LANGUAGE CXX)
