cmake_minimum_required(VERSION 3.6)
project(CLion2016_3Demo)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES main.cpp)
add_executable(CLionDemo ${SOURCE_FILES})

add_subdirectory(CPP_support)
add_subdirectory(C_support)
add_subdirectory(Resolve_context)
add_subdirectory(Doxygen_tparam)
add_subdirectory(Resolve_conflict)
add_subdirectory(font_with_ligatures)