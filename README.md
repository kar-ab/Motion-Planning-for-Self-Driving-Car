# Motion-Planning-for-Self-Driving-Car


This project is implementation of final assignment for [Motion PLanning Self Driving Cars](https://www.coursera.org/learn/motion-planning-self-driving-cars) on [Coursera- Self Driving Specialization](https://www.coursera.org/specializations/self-driving-cars)


This goal of this project is to design a Motion Planner, which creates trajectory to be followed using predefined waypoints (x and y position). The designed MOtion planning to perform following sub-modules: 

1) Following a global planning provided as waypoints 
2) Local planning using 
3) Behavioral Planning to handle traffic sign scenario, following lead vehicle
4) Avoiding a parked vehicle using static collision checking
5) Velocity profile generation 

-----

## Setup


1. Install Carla Simulator, corresponding steps can be found in [Ubuntu Guide](.../blob/master/CARLA-Setup-Guide-_Ubuntu_.pdf).
2. Make sure our python enviornment has tkinter module installed
3. Clone this project contents in "PythonClient" Folder of Carla Simulator directory

## Run

1. Run carla server on terminal using command 

	```
	$ cd <path_to_carla_simlator>
	$ ./CarlaUE4.sh /Game/Maps/RaceTrack -windowed -carla-server -benchmark 
	```
2. On another terminal, run client module 

	```$ python3 /Course4FinalProject/module_7.py```

## Results


<b>Green Line</b> Trajectory defined using waypoints

<b>Orange Line</b> Path travelled by vehicle using the designed Motion Planner

![alt_text](https://github.com/kar-ab/Motion-Planning-for-Self-Driving-Car//blob/main/Course4FinalProject/controller_output/trajectory.png?raw=true)

## Credits

University of Toronto

[Coursera](https://www.coursera.org/)
