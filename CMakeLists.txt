cmake_minimum_required(VERSION 3.12)
project(EJemplo)

set(CMAKE_CXX_STANDARD 20)

# Add your source files here
set(SOURCES
    ejemplo1.cpp
)

add_executable(MyProject ${SOURCES})