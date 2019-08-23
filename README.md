## A Collection of ROS Sensor Drivers for Projects 

### ROS version: Kinetic (Ubuntu 16.04)

#### Intel RealSense R200

$ sudo apt-get install linux-headers-generic  
$ sudo apt-get install ros-kinetic-librealsense  
  
$ roslaunch realsense_camera r200_nodelet_rgbd.launch  
$ rqt_image_view  
