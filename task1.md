
# Download Ros System
 1- Download Virtual Box   
 2- Ubuntu 20.04 installation    
 3- Install Ros System

 
### Links

[Virtual Box Download ](https://www.virtualbox.org/wiki/Downloads)  
[Ubuntu installation ](https://releases.ubuntu.com/20.04/?_ga=2.225306138.1604468304.1657696161-1049168321.1657696161) 

## Ros installation in ubuntu
open the terminal then write the following: 

##### 1- setup your sources
```bash
  sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
```
##### 2- Set up your keys
```bash
  sudo apt install curl
```
##### Then  
```bash
  curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -
```
### 3- Now for the Installation
###### First
```bash
  sudo apt update
```
### Then, Pick how much of ROS you would like to install.
###### Desktop-Full Install: (Recommended) : Everything in Desktop plus 2D/3D simulators and 2D/3D perception packages 
```bash
  sudo apt install ros-noetic-desktop-full
```

###### Desktop Install: Everything in ROS-Base plus tools like rqt and rviz
```bash
  sudo apt install ros-noetic-desktop
```
###### ROS-Base: (Bare Bones) ROS packaging, build, and communication libraries. No GUI tools.
```bash
  sudo apt install ros-noetic-ros-base
```

### 4- Environment setup
```bash
  source /opt/ros/noetic/setup.bash
```


Now, The Ros OS is downloaded. 











