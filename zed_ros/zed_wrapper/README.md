### Prerequisites

- Ubuntu 16.04
- [ZED SDK **≥ 2.3**](https://www.stereolabs.com/developers/) and its dependency [CUDA](https://developer.nvidia.com/cuda-downloads)
- [ROS Kinetic](http://wiki.ros.org/kinetic/Installation/Ubuntu)
- [Point Cloud Library (PCL)](https://github.com/PointCloudLibrary/pcl)

### Build the program

The zed_ros_wrapper is a catkin package. It depends on the following ROS packages:

   - tf2_ros
   - tf2_geometry_msgs
   - nav_msgs
   - roscpp
   - rosconsole
   - sensor_msgs
   - opencv
   - image_transport
   - dynamic_reconfigure
   - urdf

### Run the program

To launch the wrapper along with an Rviz preview, open a terminal and launch:

    $ roslaunch zed_wrapper display.launch 


To launch the wrapper without Rviz, use:

    $ roslaunch zed_wrapper zed.launch

 To select the ZED from its serial number
 
 # Replace 18214 with the actual SN

    $ roslaunch zed_wrapper zed.launch serial_number:=18214 

