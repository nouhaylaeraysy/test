cmake_minimum_required(VERSION 3.21)
project(transcription C)

set(CMAKE_C_STANDARD 99)

add_executable(transcription module_transcription.c)
