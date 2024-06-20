cmake_minimum_required(VERSION 3.1.3)

# Set name of project (as PROJECT_NAME)
project(lib_src_template)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED true)

# Add include directories
include_directories(${CMAKE_SOURCE_DIR}/include)

# Add all the sources files in src
file(GLOB SOURCES ${CMAKE_SOURCE_DIR}/src/*.cpp)

# Add main.cpp file
set(SOURCES ${SOURCES} ${CMAKE_SOURCE_DIR}/main.cpp)

# Add the executables
add_executable(${PROJECT_NAME} ${SOURCES})

#In windows, use the next command to generate de MakeFile: cmake .. -G "MinGW Makefiles"