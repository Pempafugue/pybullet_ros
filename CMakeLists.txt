cmake_minimum_required(VERSION 2.8.3)
project(pybullet_ros)

find_package(catkin REQUIRED COMPONENTS
    std_msgs
    cv_bridge
)

catkin_python_setup()
