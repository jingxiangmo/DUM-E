# DUM-E


## RVIZ
```bash
cd ros_ws
catkin build
source /opt/ros/noetic/setup.zsh    # .bash if using bash
source devel/setup.zsh              # .bash if using bash
sudo chmod 666 /dev/ttyUSB0
roslaunch rplidar_ros view_rplidar_a2m8.launch
```