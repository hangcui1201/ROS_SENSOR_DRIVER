## A Collection of ROS Sensor Drivers for Projects 

### ROS version: Kinetic (Ubuntu 16.04)

#### Intel RealSense R200

$ sudo apt-get install linux-headers-generic  
$ sudo apt-get install ros-kinetic-librealsense  
  
$ roslaunch realsense_camera r200_nodelet_rgbd.launch  
$ rqt_image_view  
  

#### HLS LFCD LDS 2D Laser

[HLS LFCD LDS 2D LASER DRIVER](https://github.com/ROBOTIS-GIT/hls_lfcd_lds_driver/tree/kinetic-devel)  

$ source devel/setup.bash  
$ roslaunch hls_lfcd_lds_driver hlds_laser.launch  