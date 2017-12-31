cmake_minimum_required(VERSION 3.9)
project(HelloWorld)

ADD_DEFINITIONS("-std=c++0x -O3")

include_directories(include)
FILE(GLOB_RECURSE sourcefiles "src/*.cpp")
add_executable( HelloWorld ${sourcefiles} )