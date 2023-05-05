
# Morewood traffic light
Jessie Fan
18-224/624 Spring 2023 Final Tapeout Project
## Overview
Functions as a traffic light & cross walk light signals 
which takes in inputs of which cars are waiting and if 
the pedestrian crossing button has been pressed. 
## How it Works
FSM-D
Uses an FSM (Moore style) to control the different states 
for each light for each car/ped waiting. Also uses 
multiple counters (to count the time allotted for cars to go
in each direction) and a register to hold whether the pedestrian
crossing button has been pressed.
To add images, upload them into the repo and use the following format to
embed them in markdown:
![](Screen Shot 2023-05-05 at 6.02.52 PM.png)
## Inputs/Outputs
(describe what each of the 12 input and 12 output pins are used for; )
(if you have any specific dependency on clock frequency; i.e. for visual
effects or for an external interface, explain it here.)
## Hardware Peripherals
(if you have any external hardware peripherals such as buttons, LEDs,
sensors, etc, please explain them here. otherwise, remove this section)
## Design Testing / Bringup
(explain how to test your design; if relevant, give examples of inputs and
expected outputs)
(if you would like your design to be tested after integration but before
tapeout, provide a Python script that uses the Debug Interface posted on
canvas and explain here how to run the testing script)
## Media
(optionally include any photos or videos of your design in action)
## (anything else)
If there is anything else you would like to document about your project
such as background information, design space exploration, future ideas,
verification details, references, etc etc. please add it here. This
template is meant to be a guideline, not an exact format that you're
required to follow.
