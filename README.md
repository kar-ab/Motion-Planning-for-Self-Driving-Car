# Motion-Planning-for-Self-Driving-Car


This project is implementation of final assignment for [Motion PLanning Self Driving Cars](https://www.coursera.org/learn/motion-planning-self-driving-cars) on [Coursera- Self Driving Specialization](https://www.coursera.org/specializations/self-driving-cars)


This goal of this project is to design a Motion Planner, which creates trajectory to be followed using predefined waypoints (x and y position). The designed MOtion planning to perform following sub-modules: 

1) Following a global planning provided as waypoints 
2) Local planning using 
3) Behavioral Planning to generatendle traffic sign scenario
4) Avoiding a parked vehicle using static collision checking
5) Velocity profile generation to follow lead vehicle

-----

## Setup


1. Install Carla Simulator, corresponding steps can be found in [Ubuntu Guide](.../blob/master/CARLA-Setup-Guide-_Ubuntu_.pdf).
2. Make sure our python enviornment has tkinter module installed
3. Clone this project contents in "PythonClient" Folder of Carla Simulator directory

## Run

1. Run carla server on terminal using command 

	`
	$ cd <path_to_carla_simlator>
	$ ./CarlaUE4.sh /Game/Maps/RaceTrack -windowed -carla-server -benchmark 
	`
2. On another terminal, run client module 

	`$ python3 /Course4FinalProject/module_7.py`


## Details

[course4_waypoints.txt](../blob/main/Course4FinalProject/course4_waypoints.txt): 

[stop_sign_params.txt](../blob/main/Course4FinalProject/stop_sign_params.txt):

[module_7.py](../blob/master/Course1FinalProject/module_7.py): Carla client to execute vehicle commands

[behavioural_planner.py](../blob/main/Course4FinalProject/behavioural_planner.py): 

[collision_checker.py](../blob/main/Course4FinalProject/collision_checker.py): 

[controller2d.py](../blob/main/Course4FinalProject/controller2d.py): 

[course4_waypoints.txt](../blob/main/Course4FinalProject/course4_waypoints.txt): 

[local_planner.py](../blob/main/Course4FinalProject/local_planner.py): 


[parked_vehicle_params.txt](../blob/main/Course4FinalProject/parked_vehicle_params.txt): 

[path_optimizer.py](../blob/main/Course4FinalProject/path_optimizer.py): 

[velocity_planner.py](../blob/main/Course4FinalProject/velocity_planner.py): 


## Results


## Credits: 

University of Toronto

[Coursera](https://www.coursera.org/)
