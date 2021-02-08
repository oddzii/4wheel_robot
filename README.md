# 4wheel_robot

A mobile robot platfrom with 4 wheels layout.
![Screenshot from 2021-01-12 08-20-25](https://user-images.githubusercontent.com/68624655/107174453-da4bae00-69fc-11eb-93ca-6029ceffd057.png)

# For watch presentation Click below !!
<p>
   <a target="_blank" rel="noopener" href="https://www.canva.com/design/DAES-s6edVg/wbL7giU7Nh73_EDcSIsxaQ/view">
      <img src="https://user-images.githubusercontent.com/68624655/107232258-cb441a80-6a53-11eb-9397-5b1126d1c503.png" alt="screenshot" style="max-width:100%;">
   </a>
</p>


# Install Required Dependencies

The first step is to download the myrobot packages from the Github repository.This includes the following ROS packages used for simulation as well as operation of myrobot.

   - myrobot_description: Robot description (URDF)
   - myrobot_gazebo : for simulation
   - myrobot_slam: for create a map
   - myrobot_navigaion: for autonomous movement

Since these packages are installed from source, they need to be installed in the catkin folder. They can be built with the following command:

```
  cd ~/catkin_ws/src
  git clone https://github.com/ros-perception/slam_gmapping.git
  git clone https://github.com/ros-planning/navigation.git
  git clone https://github.com/oddzii/4wheel_robot.git
  cd ~/catkin_ws/
  catkin_make
```
the following packages are the ones that are required for use with myrobot platform.
```
sudo apt-get install ros-melodic-teleop-twist-joy 
sudo apt-get install ros-melodic-robot-localization
sudo apt-get install ros-melodic-joint-state-controller
sudo apt-get install ros-melodic-dwa-local-planner
sudo apt-get install ros-melodic-rviz-imu-plugin
```
