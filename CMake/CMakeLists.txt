cmake_minimum_required(VERSION 3.16)
project(cpp20Testnewfeature LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(main src/main.cpp)