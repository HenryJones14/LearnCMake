# Top-level CMake project file, do global configuration
cmake_minimum_required(VERSION 3.25)



# Create solution
project("TestSolutionName")


set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ../../Builds/$<CONFIG>-$<PLATFORM_ID>-${CMAKE_SYSTEM_PROCESSOR})

# Create EXE
add_executable("TestExicutable" ../../Source/Executable/main.cpp)



# Set the C++ standard to C++ 20
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)