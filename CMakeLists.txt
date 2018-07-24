cmake_minimum_required(VERSION 2.8.3)
project(manos_vision)

add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
    usb_cam
    astra_launch)

catkin_package()

include_directories()
