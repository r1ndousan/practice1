cmake_minimum_required(VERSION 3.10) 

project(HelloWorld LANGUAGES CXX)     

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(helloworld helloworld.cpp)
