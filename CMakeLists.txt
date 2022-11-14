cmake_minimum_required(VERSION 3.5)
project(gary_ros2)

if(NOT CMAKE_C_STANDARD)
    set(CMAKE_C_STANDARD 99)
endif()

if(NOT CMAKE_CXX_STANDARD)
    set(CMAKE_CXX_STANDARD 14)
endif()

find_package(ament_cmake REQUIRED)

find_package(gary_hardware REQUIRED)
find_package(gary_simulation REQUIRED)
find_package(gary_controllers REQUIRED)
find_package(gary_msg REQUIRED)
find_package(gary_description REQUIRED)

ament_package()
