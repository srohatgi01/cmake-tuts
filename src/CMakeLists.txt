cmake_minimum_required(VERSION 3.2)
project(HelloApp
        VERSION 0.0.1
        DESCRIPTION "The simeple Hello World App"
        LANGUAGES CXX)
add_executable(HelloAppBinary main.cpp log.cpp)

target_include_directories(HelloAppBinary PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include)