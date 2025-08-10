# Checkpoint 20

This ROS2 package is for the bringup of the ROS2 drivers for Fasbot robot car.

To use this:-

git clone https://github.com/robkwan/checkpoint20.git under the local ~/ros2_ws/src folder.

then inside ~/ros2_ws folder, execute "colcon build" to build all the files.

then "source install/setup.bash" in the ~/ros2_ws folder.

then "ros2 launch fastbot_bringup bringup.launch.xml" will launch all the ROS2 drivers for Fastbot.

then "ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args --remap cmd_vel:=/fastbot/cmd_vel" in another terminal or check the related ros2 topic for Fastbot with "ros2 topic list" for different operations.
