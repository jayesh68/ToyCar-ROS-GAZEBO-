# Teleoperation of 4 Wheeled Robot in Gazebo.

## Project Details
1. Developed a CAD model of a 4-wheeled robot.
2. Developed the XACRO using the URDF.
3. Added controllers and transmissions to control the robot wheels.
4. Used ROS publishers and subscribers to puslish to different topics to teleoperate he robot in different directions in a custom Gazebo World.

## Steps to run the simulation
1. Clone the repository to a folder named as ToyCar.
2. Perform Catkin build and source the bashrc.
3. Run the command roslaunch ToyCar toy_car.launch to launch the CAD model in gazebo
4. Run the command rosrun ToyCar teleop_tamplate.py to teleoperate the robot in gazebo.
