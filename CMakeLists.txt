cmake_minimum_required(VERSION 3.3)

project(escapepod)

add_compile_options(-Wall -Wextra -Wpedantic -Werror)

set(CMAKE_CXX_STANDARD 23)

add_executable(${PROJECT_NAME}
        src/main.cpp
        src/util/HttpFileParser.h
        src/util/HttpFileParser.cpp
)
