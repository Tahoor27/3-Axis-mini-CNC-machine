Project Details:
The following project details will include the following subjects: 
•	Project Description 
•	Mechanical Details 
•	Code specifications (libraries and dependencies etc.)
•	Generating G-code 
Project description: 
•	The project is a mini CNC machine or a X-Y plotter, that moves along three axes to draw any image uploaded onto it.
Mechanical Details: 
•	Two stepper motors from scrap DVD-ROMS are used to move along the x and y axis. A servo motor with a pen attached to it controls the z motion, that is the up-down motion of the pen. 
•	L293d motor shield along with the Arduino UNO is used as the motor controller. 
•	The shield provides control for two stepper motors and two servo motors. 
•	Wires are to be soldered on the steppers. For each stepper two wire pairs should show continuity. 
•	Heat sinks can be attached for better performance. 
 
Code Specifications: 
There are two parts: 1) the Arduino’s firmware 2) The processing Code for communicating with the serial monitor. 
Firmware for Arduino: 
•	The code can be accessed from: https://github.com/Tahoor27/3-Axis-mini-CNC-machine
•	The respective library corresponding to the motor driver is to be used. In case of the l293d motor shield the ADAFRUIT – motor shield library is used, it can be downloaded from: https://learn.adafruit.com/adafruit-motor-shield/library-install
•	Info for stepper class is given here: https://learn.adafruit.com/afmotor-library-reference/af-stepper-class
•	Motor speeds / efficiency can vary, therefore introducing a step delay or a line delay can improve results. 
Processing: 
•	Processing IDE would be used to communicate the g-code with the Arduino’s serial monitor. 
•	It can be downloaded from (download any version above 3): https://processing.org/download/
•	The GCTRL code can be accessed from: https://github.com/Tahoor27/3-Axis-mini-CNC-machine
•	For more info: https://www.instructables.com/id/How-to-Make-Mini-CNC-2D-Plotter-Using-Scrap-DVD-Dr/

Generating G-Code:
•	G-code can be generated from an open source software called ‘Inkscape’.  It can be downloaded from: https://inkscape.org/release/inkscape-0.92.4/
•	Download the g-code extension for Inkscape from: https://github.com/martymcguire/inkscape-unicorn/
•	The Document properties for Inkscape are to be changed to: (80 x 80) mm 
•	The images should have width and height of (40 x 40) mm 
•	Before saving the image as g-code, the bit map of the image is to be created. 
•	For more info: https://www.youtube.com/watch?v=GmcmdVhCqu4

 




