# Top-level CMake project file, do global configuration
cmake_minimum_required(VERSION 3.25)



# Create solution
project("TestSolutionName")

# Create EXE
add_executable("TestExicutable" test.cpp)

# Create Project
# add_subdirectory ("TestProjectName")



# Set the C++ standard to C++ 20
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)