cmake_minimum_required (VERSION 3.16)
project (Nerv)
set(CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake_modules" ${CMAKE_MODULE_PATH})
add_subdirectory(deps)
add_executable (Nerv src/main.cpp)
target_link_libraries (Nerv eigen)
#t