#
#  CMakeLists.txt
#
#  Created on: Jun 16, 2016
#      Author: Dennis Sitelew
#

cmake_minimum_required(VERSION 2.8)

project(HeaderGuards)

set(${CMAKE_PROJECT_NAME}_SOURCES
   ${CMAKE_CURRENT_LIST_DIR}/main.cpp
)

add_executable(${CMAKE_PROJECT_NAME}_EXECUTABLE ${${CMAKE_PROJECT_NAME}_SOURCES})
set_target_properties(${CMAKE_PROJECT_NAME}_EXECUTABLE PROPERTIES OUTPUT_NAME ${CMAKE_PROJECT_NAME})
