cmake_minimum_required(VERSION 3.0.2)
project(camera)

find_package(catkin REQUIRED COMPONENTS
sensor_msgs
cv_bridge
rospy
std_msgs
)

catkin_package()



