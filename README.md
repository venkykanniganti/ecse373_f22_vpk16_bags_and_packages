# How to launch the previous version of robot description


```
# To run code with default parameters:
roslaunch navvis_description navvis.launch

#To run the node with no GUI, run the following.
roslaunch navvis_description navvis.launch use_xacro:=true use_joint_state_publisher_gui:=false
```

# How to launch the new version of robot description

```
roslaunch navvis navvis.launch bag_file:=/path/to/bag-file rviz_config_type:=no_track
```

rviz_config_type can be varied between no_track, track, no_map, and original. This new navvis launcher can launch the old robot and the new seamlessly.
