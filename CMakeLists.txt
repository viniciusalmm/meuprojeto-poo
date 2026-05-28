cmake_minimum_required(VERSION 3.20)

project(pixelwave_fm CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(pixelwave_fm
    src/main.cpp
    src/music.cpp
    src/playlist.cpp
    src/listener.cpp
    src/radio_station.cpp
)

target_include_directories(pixelwave_fm PRIVATE src)