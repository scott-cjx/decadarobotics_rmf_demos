cmake_minimum_required(VERSION 3.5.0)

project(decadarobotics_rmf_demos)

find_package(ament_cmake REQUIRED)

install( DIRECTORY
  launch
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
