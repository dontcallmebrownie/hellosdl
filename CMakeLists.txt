cmake_minimum_required(VERSION 3.16)
project(hellosdl)

# set the output directory for built objects.
# This makes sure that the dynamic library goes into the build directory automatically.

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}/$<CONFIGURATION>")
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}/$<CONFIGURATION>")

add_subdirectory(vendor)
add_subdirectory(src)
