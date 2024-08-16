cmake_minimum_required(VERSION 3.24)
idf_component_register(
    SRCS "Time.cpp"  # Add all source files here
    INCLUDE_DIRS "./" 
    REQUIRES  "arduino" # Add include directories here
)