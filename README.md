# Turtlesim Catch Them All 🐢🎯

A ROS 2 project that controls turtlesim to detect, chase, and kill spawned turtles automatically.

## Features
- Custom ROS 2 interfaces (msg/srv)
- Launch files for easy startup
- Automated turtle killing logic

## Packages
- `turtlesim_catch_them_all`
- `my_robot_interfaces`
- `my_robot_bringup`

## How to Run
```bash
colcon build
source install/setup.bash
ros2 launch my_robot_bringup turtlesim_catch_them_all.launch.xml
