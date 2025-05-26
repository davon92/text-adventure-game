cmake_minimum_required(VERSION 3.15)
project(text_adventure_game)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(text_adventure_game
    src/main.cpp
    src/game.cpp
    src/room.cpp
    src/player.cpp
)
