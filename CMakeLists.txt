cmake_minimum_required( VERSION 3.16 )
project( mul2 )

add_library( mul2 src/mul2.cpp )
target_include_directories( mul2 PUBLIC include )

