# racecar_sim
Ubuntu20+ros-Noetic  

### 1：Install for Dependence

```shell
sudo apt-get install ros-noetic-ackermann-msgs
sudo apt-get install ros-noetic-navigation
sudo apt-get install ros-noetic-openslam-gmapping
sudo apt-get install ros-noetic-geographic-info
sudo apt-get install ros-noetic-controller-manager
sudo apt-get install ros-noetic-gazebo-ros-control
sudo apt-get install ros-noetic-effort-controllers
sudo apt-get install ros-noetic-joint-state-controller 
sudo apt-get install ros-noetic-position-controllers  
sudo apt-get install ros-noetic-teb-local-planner
```

### 2：If Gazebo can't be launched:

```shell
cd ~/.gazebo/
git clone https://github.com/osrf/gazebo_models.git models

sudo chmod 777 ~/.gazebo/models
sudo chmod 777 ~/.gazebo/models/*
```
### 3: Simulator launch:

```shell
roslaunch racecar_simulator racecar_gazebo_rviz.launch
rosrun racecar_description keyboard_teleop.py
```

### 4: Reference:
	https://gitee.com/zeende/racecar_sim

# Simulator_Noetic
