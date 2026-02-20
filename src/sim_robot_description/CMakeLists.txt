cmake_minimum_required(VERSION 3.8)
project(sim_robot_description)

find_package(ament_cmake REQUIRED)

install(DIRECTORY urdf launch config models
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
