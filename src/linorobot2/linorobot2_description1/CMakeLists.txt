cmake_minimum_required(VERSION 3.5)
project(linorobot2_description1)

find_package(ament_cmake REQUIRED)
find_package(urdf REQUIRED)

install(
  DIRECTORY launch urdf rviz
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
