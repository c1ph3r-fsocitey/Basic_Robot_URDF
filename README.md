# Basic_Robot_URDF
This is a basic robot URDF file which can be interacted using the joint state publisher

[first_urdf_robot.webm](https://github.com/c1ph3r-fsocitey/Basic_Robot_URDF/assets/109020327/edd76e98-6829-4a08-8447-428a7e32383a)

## Steps to run the URDF file

## Step 1: Make sure ROS 2 is installed
you can read more about ROS 2 [here](https://docs.ros.org/en/humble/Installation.html)

## Step 2: Clone the repository
use the following command to clone the repository
```
git clone https://github.com/c1ph3r-fsocitey
```

## Step 3: Locate and navigate to the directiry 
```
ls
cd Basic_Robot_URDF
```

## Step 4: Build the repository
building the repository is a crucial step to make sure the program works
```
colcon build --packages-select Basic_Robot_URDF
```

## Step 5: Execute the python file
```
ros2 launch Basic_Robot_URDF display.launch.py
```
## or Execute the XML file
```
ros2 launch Basic_Robot_URDF display.launch.py
```
