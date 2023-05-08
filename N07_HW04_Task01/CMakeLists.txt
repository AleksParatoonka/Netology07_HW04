cmake_minimum_required(VERSION 3.10)

project(N07_HW04_Task01)

find_package(Catch2 CONFIG REQUIRED)

add_executable(N07_HW04_Task01 "N07_HW04_Task01.cpp")
target_link_libraries(N07_HW04_Task01 PRIVATE Catch2::Catch2WithMain)