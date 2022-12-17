cmake_minimum_required(VERSION 3.17)

project(mouseHub CXX)

add_executable(mouseHub 
mouse.cpp
)

target_link_libraries(mouseHub 
 -lX11
)

# add_subdirectory()
# include_directories()