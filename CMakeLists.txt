cmake_minimum_required(VERSION 3.28)
project(chiaki_builds)

set(CMAKE_CXX_STANDARD 17)

add_executable(chiaki_builds main.cpp
        chiaki/lib/src/streamconnection.c)
