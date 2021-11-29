cmake_minimum_required(VERSION 3.20)
project(untitled)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled main.cpp Game.cpp Game.h Player.cpp Player.h Dungeon.cpp Enemies.cpp Enemies.h Screen.cpp Screen.h fov.cpp fov.h)
