cmake_minimum_required(VERSION 3.0.2)
project(ci_test)

find_package(catkin REQUIRED
  COMPONENTS
)

catkin_package(
  INCLUDE_DIRS
  LIBRARIES
  CATKIN_DEPENDS
  DEPENDS
)
