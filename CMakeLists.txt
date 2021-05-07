cmake_minimum_required(VERSION 3.0)

project(where C)

add_definitions(-DUNICODE -D_UNICODE)

add_executable(where where.c where.rc)
target_link_libraries(where msvcrt kernel32)
