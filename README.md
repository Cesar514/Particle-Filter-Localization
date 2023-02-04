# Particle Filter Based Localization
 

![Particle Filter](https://raw.githubusercontent.com/Cesar514/Kalman-Cart-Prediction/main/final_project/map1.png)

```
 cd catkin_ws
 catkin_make
 source devel/setup.bash
 roscore
 rosrun map_server map_server map.yaml
 rosrun rviz rviz
 rosrun stage_ros stageros src/socspioneer/data/meeting.world
 roslaunch socspioneer keyboard_teleop.launch
 rosrun pf_localisation node.py
```

