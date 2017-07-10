cmake_minimum_required( VERSION 2.8 )
project( geometry )

# 添加Eigen头文件
#include_directories( "/usr/include/eigen3" )
include_directories( /Users/ives/Git/slambook/eigen3.3.4 )
add_executable( eigenGeometry eigenGeometry.cpp )
