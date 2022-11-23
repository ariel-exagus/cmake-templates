# Set minimun required version of CMake
cmake_minimum_required(VERSION 3.12)

# Set name of project (as PROJECT_NAME)
project(basic_template)

# Tell CMake where to find the executable source file
add_executable(${PROJECT_NAME}
    main.cpp
)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

#In windows, use the next command to generate de MakeFile: cmake .. -G "MinGW Makefiles"
