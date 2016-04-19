# Project-BedRock-Sensor
In this project, I analyse data from an accelerometer sensor placed under a patient's bed.
The "rms value finder" part of the code is written by me while my project teacher contributed to the "amplitude signal" part.

How to use the Program:

This program uses python 3.0
Download and store the ipython notebook file and the data file (after unzipping it) in the same folder. Run the ipython notebook file. Two figures will be seen; one shows the amplitude plot from an accelerometer sensor and the second calculates the rms values of the amplitude signal over specific intervals of time. 


About the Program:

Overview: Using matplotlib and some basic looping operations, displacement data obtained from an accelerometer sensor can be plotted against time. But how does one detect the presence of noise in the signal? Identifying the “exclusive noise” signal is key and this can be done by locating a period of signal corresponding to the time when the bed is vacant. Such a period of time will have a low intensity of amplitude compared with the time when the bed is occupied and registers a patient’s motion. For the purpose of finding this “exclusive noise” signal, this program calculates the rms values of the amplitude signal over specific intervals of time. A much lower rms value compared to the average rms value indicates the possibility that the signal corresponding to the low rms value is “exclusive noise” signal.

The attached program (python notebook file) plots data from an accelerometer sensor and then calculates the rms values of the amplitude signal over specific intervals of time. 


About the Project:

The project analyses data from an accelerometer sensor placed under patients' beds. A correlation between the movement of the bed and patients’ quality of sleep is one of the objectives of the analysis. Another is to explore the possibility to use the sensor data to recognize conditions such as seizures that call for immediate attention from the attending staff. If the correlation between such data and condition is made, then the accelerometer sensor could be hooked to an online monitoring system that triggers an alarm when data pattern corresponding to such conditions is noticed.

In the first phase of the project, the focus is on the quality of data (how to identify noise; what is the percentage of noise in the data, etc.) and to examine whether the data quality changes with different kinds of bed materials.

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

