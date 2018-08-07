#note one
*更改文件virtual_joystick.py中的发布(publisher)乌龟的订阅相同 turtle/cmd_vel然后在ros_ws/src/turtlesim_bringup/launch中touch demo2.launch Then gedit demo2.launch   change"turtlesim"to"mx_teleop" change"turtlesim_node"to"virtual_joystick.py" finally roslaunch demo2.launch
*
*
