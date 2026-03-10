cmake_minimum_required(VERSION 3.16)

project(ZombieGame)

set(CMAKE_CXX_STANDARD 20)

find_package(SFML 2.6 REQUIRED COMPONENTS graphics window system)

add_executable(ZombieGame src/main.cpp)

target_link_libraries(ZombieGame
    sfml-graphics
    sfml-window
    sfml-system
)