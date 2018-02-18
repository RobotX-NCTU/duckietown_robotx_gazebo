# duckietown_robotx_gazebo
This repo include 3 repo, due to dependency  
*   [robotx_forum tutorial](https://github.com/RobotX-NCTU/robotx_forum_tutorials)  
*   [bamboo_lake_gazebo](https://github.com/RobotX-NCTU/bamboo_lake_gazebo)    
*   [marine_duckiebot](https://github.com/RobotX-NCTU/marine_duckiebot)  
## clone
```
git clone --recursive git@github.com:RobotX-NCTU/duckietown_robotx_gazebo.git
```

## build
```
cd duckietown_robotx_gazebo/
source dependencies_common.sh
cd catkin_ws/
catkin_make
```

### environment.sh
You should run environment.sh before doing something in this package


## About bamboo_lake_gazebo
all model world
```
roslaunch bamboo_lake_gazebo all_model.launchs
```
![](https://i.imgur.com/R25JCxL.jpg)
