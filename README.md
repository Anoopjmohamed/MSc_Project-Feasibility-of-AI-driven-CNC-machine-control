Feasibility study to control the CNC machine using AI modelling.
This Porject is performed as part of my MSc degree.
The aim of the project is to determine the fault daignosis and motion control of a 3 axis CNC machine based on the fault diagnosis to be performed solely based on the AI modelling. 

Stage1: An experimental run of 3D printer is conducted, 3D printer is selected as the 3 axis CNC machine as it was readily available in the lab.

The experimental run is performed using Arduino UNO microcontroller and Stepper motor dirver for the X axis of the CNC machine. Arduino will give motion control commands to the stepper driver and the driver will drive the motor accordingly. 

Stage2: Using ADXL 345 accelaration sensor and Arduino MEGA the vibration data of the spindle movement along the X axis of the CNC machine is recorded. It is observed that the peaks of vibration occured at the left and right limits along the Axis for spindle movement. 

Stage3: A fault condition is simulated by introducing a bump in the path of the spindle along the X axis. Now the vibration peak is observed for the spinble at the bump along with at the limits. However its observed that the mainutude of vibration at the limits are higher than the magnitude of the vibration at the fault. 

Stage4: Both these data sets with fault and normal operating is recorded into a .CSV file using Python script, by rallying the data obtained using Arduino MEGA is USB serial communicated into the Python script. 



# MSc-Project-AI-driven-CNC-machine-control
refer https://github.com/mikeroyal/Deep-Learning-Guide
