# ROS-installation
## ROS installation on PC
In this guide I will show how to install ros noetic on ubuntu 20.04 (specially for windows users) 
* Install virtual box from the [the virtual box website](https://www.virtualbox.org/)
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture1.png)
* Choose your OS (windose on my case) & install it as any regular program 
* Download the iso file for ubuntu system ( version 20.04) from [Ubuntu Focal Fossa](https://releases.ubuntu.com/20.04/)
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture2.png)
* Open the virtual box, click the new icon and put a name for your new system & choose the system tybe & version ( Linux , ubuntu 64 bit) 
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture3.png)
* Click the setting icon to modify the system features , the most important thing is to provide the ubuntu iso file by going to storage and clicking on the cd icon ( like in the picture) 
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture4.png) 
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture5.png)
* Click the start Icon
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture6.png)
* Click intsall ubuntu & countinue in the intsall processing 
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture7.png)
* When the installation is done , it will look like this
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture8.png)
* By following the instructions from [wiki ros](http://wiki.ros.org/noetic/Installation/Ubuntu)
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture9.png)
* By copying the instructions & pasting it in the terminal 
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture10.png)
* When it done installation, check by roscore command, should return like this 
![alt text](https://github.com/Maashn5/ROS-installation/blob/main/Picture11.png)
## ROS installation on jetson nano
must install ubuntu or xubuntu in the jetson nano (on its SD card) 
![alt text](https://cdn.stereolabs.com/blog/wp-content/uploads/2019/03/microsd-card-jetson-nano.jpg)
* First install the image from any source in the internet or from [NVIDIA](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write)
* Then flashing the image in the SD card by any third party program like [Etcher](https://www.balena.io/etcher/)
* Putting the SD card in the jetson nano ,then run it & completing the setup of ubuntu 
* When it's complete, you can install ros as previous or you can follow these instructions [ROS installation on jetson nano](https://www.stereolabs.com/blog/ros-and-nvidia-jetson-nano/)
