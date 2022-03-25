cmake_minimum_required(VERSION 3.10)

# set the project name
project(sample)
find_package(PkgConfig REQUIRED)
find_package(OpenCV REQUIRED)
find_package(Libcamera REQUIRED)
# add the executable
add_executable(Hello Hello.cxx)
