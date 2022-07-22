
# Installing ROS Melodic On Ubuntu 18.04

These are the steps of installing ROS Melodic onUbuntu 18.04. the steps are taken from [Wiki.ROS](http://wiki.ros.org/melodic/Installation/Ubuntu). Before starting with the installation process, the system has to be ubdated. 


## Installation

After opennging the terminal the following commands should be entered.

1-
```bash
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
```

2-
```bash
sudo apt install curl
```

3-
```bash
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -

```
4-
```bash
sudo apt update

```
5-
```bash
sudo apt install ros-melodic-desktop-full

```

6-
```bash
apt search ros-melodic
```

7-
```bash
sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential
```

8-
```bash
sudo apt install python-rosdep

```

9-
```bash
sudo rosdep init

```

10-
```bash
rosdep update

```

11-
```bash
  npm install my-project
  cd my-project
```
    
## Screenshots
<p align="center">

![App Screenshot](https://github.com/AbdullahAlshambri/InstallingROSMelodic/blob/main/Steps/1.png)
![App Screenshot](https://github.com/AbdullahAlshambri/InstallingROSMelodic/blob/main/Steps/2.png)
![App Screenshot](https://github.com/AbdullahAlshambri/InstallingROSMelodic/blob/main/Steps/3.png)
![App Screenshot](https://github.com/AbdullahAlshambri/InstallingROSMelodic/blob/main/Steps/4.png)
![App Screenshot](https://github.com/AbdullahAlshambri/InstallingROSMelodic/blob/main/Steps/5.png)
![App Screenshot](https://github.com/AbdullahAlshambri/InstallingROSMelodic/blob/main/Steps/6.png)
![App Screenshot](https://github.com/AbdullahAlshambri/InstallingROSMelodic/blob/main/Steps/7.png)
</p>
