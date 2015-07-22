talos_teleop
============

Teleoperation package and launch files for the Talos robot

Usage:

roslaunch talos_teleop talos_teleop2.launch joystick:=false

Should be run after the simulator is running. On the real robot pass in joystick:=true which will then looked for the paired PS3 controller.
