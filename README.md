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

## Hector SLAM
```bash
cd ros_ws
catkin build
source /opt/ros/noetic/setup.zsh    # .bash if using bash
source devel/setup.zsh              # .bash if using bash
sudo chmod 666 /dev/ttyUSB0
roslaunch rplidar_ros view_rplidar_a2m8.launch
# then, open a new terminal window
source /opt/ros/noetic/setup.zsh    # .bash if using bash
source devel/setup.zsh        
roslaunch hector_slam_launch tutorial.launch 
```