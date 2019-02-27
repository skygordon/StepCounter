# StepCounter
Counts Steps and Displays on LCD Screen

Utilizes: ESP32, IMU, LCD 1.8", 

Description:

Averages acceleration in order to tell if a step has been taken 
and displays the current step count to the LCD screen.
Reload program to begin again at zero.

a step counting algorithm that can at least reasonably count your steps by 
walking around the room when given the averaged acceleration magnitude. 
You can test your step counter by mimicking steps via gentle drops on a table, 
and once that looks good, by walking around with it and comparing the number of 
steps reported with the number of steps you actually took.
