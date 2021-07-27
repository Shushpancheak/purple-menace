cmake_minimum_required(VERSION 3.11)

project(purple-menace-bot)

add_subdirectory(submodules/sleepy-discord)

add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME} sleepy-discord)