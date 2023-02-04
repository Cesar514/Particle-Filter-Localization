# Particle Filter Based Localization

[Robot Localization Based on Particle Filter](https://github.com/Cesar514/Particle-Filter-Localization/blob/09db4a752ec69f66e801f8ccaf2484b427006c24/pf_localisation/Robot%20Localization%20Based%20on%20Particle%20Filter.pdf)
 
In the case of robotics and artificial intelligence, the first and most important task is to determine where the mobile robot is, in other words, is the ‘Localization’. There are several methods for mobile robot localization, such as Kalman filter, Grid-based Markov Localization, and the Monte Carlo Localization (Particle filter). The most popular Localization method recently - Monte Carlo method or Particle filtering makes an optimal trade-off between the accuracy and robustness. The particle filter describes the probabilistic distribution based on sampling method. It samples the map according to the prior or the probability that are known, then give every particle a weight number as the symbol of the probability. After the iterations, the estimate pose of the robot will be converged accurately.

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

