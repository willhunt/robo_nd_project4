# Project 4, Map My World
## Udacity Robotics Software Engineer Nanodegree
Map My World project for the Robotics Software Engineer Nanodegree program from Udacity.

## How to Launch the simulation?

#### Clone the package
```sh
$ cd /home/<project folder>/ 
$ git clone https://github.com/willhunt/robo_nd_project4.git
```

#### Build the `robo_nd_project3` package
```sh
$ catkin_make
```

#### Make sure to check and install any missing dependencies
```sh
$ rosdep install --from-paths src --ignore-src -r -y
```

#### After building the package, source your environment
```sh
$ source devel/setup.bash
```

#### Once the `robo_nd_project4` package has been built, you can launch using:
```sh
$ roslaunch myrobot_main main.launch
```
#### Inspect mapping database
```sh
$ rtabmap-databaseViewer ~/.ros/rtabmap.db
```

## Mapping Results
62 loop closures detected with 3 passes through the enviornment using approximately the same path (via teleoperation).  
Rtab database copy stored in /rtab_database_archive.
#### Final map
<img src="/media/rtab_map.png" alt="rtab map image" width="250" height="250">
<img src="/media/gazebo_world.png" alt="world image" width="250" height="250">

#### Loop Closures
<img src="/media/loop_closures.png" alt="loop closures image" width="250" height="250">