cmake_minimum_required(VERSION 3.8)
project(P1)

set(CMAKE_CXX_STANDARD 11)

if (WIN32)
    set(CMAKE_CXX_FLAGS -fexec-charset=gbk)
endif ()

set(SOURCE_FILES main.cpp LinkList.h LinkNode.h ExamineeInfo.cpp ExamineeInfo.h)
add_executable(P1 ${SOURCE_FILES})