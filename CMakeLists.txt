cmake_minimum_required(VERSION 3.11-3.18)


project(SHA256)

add_library(SHA256
    src/SHA256.cpp
)

target_include_directories(${PROJECT_NAME}
    PUBLIC ${PROJECT_SOURCE_DIR}/include)
