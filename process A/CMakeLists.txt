cmake_minimum_required(VERSION 2.8)
project( processA )
find_package( OpenCV REQUIRED )
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable( processA process.cpp )
target_link_libraries( processA ${OpenCV_LIBS} )
