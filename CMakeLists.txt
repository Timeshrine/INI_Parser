cmake_minimum_required(VERSION 3.23)
project(INI_Parser)

set(CMAKE_CXX_STANDARD 14)

add_executable(INI_Parser main.cpp IniFile.cpp IniFile.h)
