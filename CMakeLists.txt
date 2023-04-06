cmake_minimum_required(VERSION 3.13)  # CMake version check
project(TP3-IFT2425)               # Create project "simple_example"
set(CMAKE_CXX_STANDARD 14)            # Enable c++14 standard

# Add main.cpp file of project root directory as source file
set(SOURCE_FILES TP3-IFT2425-I.cpp)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(tp3 ${SOURCE_FILES})
# Link X11
target_link_libraries(tp3 X11)