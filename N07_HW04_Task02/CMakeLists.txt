cmake_minimum_required(VERSION 3.10)

project(N07_HW04_Task02)

add_subdirectory("D:/coding/Netology07_HW04/Catch2" Catch2-build)

add_executable(N07_HW04_Task02 "N07_HW04_Task02.cpp")
target_link_libraries(N07_HW04_Task02 PRIVATE Catch2::Catch2WithMain)