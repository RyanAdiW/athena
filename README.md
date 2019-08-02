# athena
`athena` is the name of Universitas Indonesia Robotics Team competing on Kontes Robot Terbang Nasional 2019 (KRTI 2019) on Vertical Take-Off Landing category.

### How To
It is a ROS Package. To use it, clone this inside `your_ros_workspace/src/` directory and then on `your_ros_workspace` directory, run `catkin_make`

### Dependencies
- [`pid`](http://wiki.ros.org/pid) package
- [`rosserial_server`](http://wiki.ros.org/rosserial_server) package

### To Do
- Add `servo_utils` on `/include/athena/copter.h`
- Add `vision.cpp` (don't forget to edit `CMakeLists.txt` and `/launch/waypoint_method.launch`)
- Add arduino source code on `src/ino/`
