# Set minimun required version of CMake
cmake_minimum_required(VERSION 3.12)

# Set name of project (as PROJECT_NAME)
project(basic_template)

# Tell CMake where to find the executable source file
add_executable(${PROJECT_NAME}
    main.cpp
)