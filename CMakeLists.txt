cmake_minimum_required(VERSION 3.23)
project(Final_Project)

set(CMAKE_CXX_STANDARD 14)

add_executable(Final_Project cmake-build-debug/main.cpp cmake-build-debug/fsInode.cpp cmake-build-debug/fsInode.h cmake-build-debug/fsDisk.cpp cmake-build-debug/fsDisk.h cmake-build-debug/FileDescriptor.cpp cmake-build-debug/FileDescriptor.h)
