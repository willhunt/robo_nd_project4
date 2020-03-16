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

#### Once the `robo_nd_project3` package has been built, you can launch using:
```sh
$ roslaunch myrobot_main main.launch
```

## Evidence of Localisation
#### Teleoperated Localisation  
Localisation during teleoperation through rqt.  
<img src="/media/localisation_teleop1.gif" alt="localisation gif" width="250" height="250">

#### Naviagation Localisation
Localisation during navigation to goal using move_base.  
<img src="/media/localisation_nav1.gif" alt="localisation gif" width="250" height="250">