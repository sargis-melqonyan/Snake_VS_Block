cmake_minimum_required(VERSION 3.10)

# Set the project name
project(Snake_VS_Block)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Include directories
include_directories(inc)

# Add source files
file(GLOB SOURCES "src/*.cpp")

# Find the ncurses package
find_package(Curses REQUIRED)
include_directories(${CURSES_INCLUDE_DIR})

# Add the executable
add_executable(Snake_VS_Block ${SOURCES})

# Link the ncurses library
target_link_libraries(Snake_VS_Block ${CURSES_LIBRARIES})

# Enable debug information
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")

