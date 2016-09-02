## raspberrypi_launch description
- smart car based on ROS launch files under raspberrypi
- including hector_slam, amcl and move_base launch files

## how to use
```shell
# git clone into your catkin workspace
cd ~/my_catkin_ws/src
git clone https://github.com/Durant35/raspberrypi_launch.git
cd ..
source devel/setup.sh
```
- launch hector_slam
```shell
roslaunch raspberrypi_launch hector_slam_networking.launch
```
- launch amcl
```shell
roslaunch raspberrypi_launch amcl_networking.launch
```
- launch navigation
```shell
roslaunch raspberrypi_launch move_base_networking.launch
```