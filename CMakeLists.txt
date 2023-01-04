project(FaustMemoryAllocator)


cmake_minimum_required(VERSION 3.14)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(faustmemoryallocator SHARED src/FaustMemoryAllocator.cpp )
target_include_directories(faustmemoryallocator PRIVATE include)

