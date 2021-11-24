# config-folder
confg folder for the klipper prototype

#z tilt indication
the function z tilt will perform the probing operation at the height specified by horizontal_move_z 
SO before issuing this command is better to issue the homing command and, eventually to apply an offset to
avoid probing problem
a negative offset eg SET_GCODE_OFFSET X=-10 will incease probe at the position 30,24 instead of 20,24
This modification has not been performedas offsets must be used with special care
