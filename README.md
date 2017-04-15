# pff_ros

The ROS package depends on gazebo_ros, joint_state_publisher, robot_state_publisher, rviz and urdf. 

The dependencies can be listed using
```
rospack depends1 pff_ros
```

To visualize the differential drive robot using rviz, use following command
```
roslaunch pff_ros display_rviz.launch
```

In case it is hard to run the code, the result of the roslauch command to visualize robot is attached as image below. 

![alt text](https://github.com/AnkitSaini/pff_ros/blob/master/pff_ros_rviz.png)
