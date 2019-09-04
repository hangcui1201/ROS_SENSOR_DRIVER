## A Collection of ROS Sensor Drivers for Projects 

### ROS version: Kinetic (Ubuntu 16.04)

#### HLS LFCD LDS 2D Laser

[HLS LFCD LDS 2D LASER DRIVER](https://github.com/ROBOTIS-GIT/hls_lfcd_lds_driver/tree/kinetic-devel)  

$ source devel/setup.bash  
$ roslaunch hls_lfcd_lds_driver hlds_laser.launch  
  
#### Camera Calibration

$ roslaunch usb_cam usb_cam.launch  

$ rosrun camera_calibration cameracalibrator.py --size 8x6 --square 0.025 image:=/usb_cam/image_raw camera:=/usb_cam --no-service-check  

$ rosrun camera_calibration_parsers convert head_camera.yaml head_camera.ini  

#### Intel RealSense R200 Stereo Camera

$ sudo apt-get install linux-headers-generic  
$ sudo apt-get install ros-kinetic-librealsense  
  
$ roslaunch realsense_camera r200_nodelet_rgbd.launch  
$ rqt_image_view  
  
#### ZED Stereo Camera

[ZED ROS WRAPPER](https://github.com/stereolabs/zed-ros-wrapper)  

$ source devel/setup.bash  
$ roslaunch zed_wrapper zed.launch  

$ source devel/setup.bash  
$ roslaunch zed_display_rviz display_zed.launch    




