# Motor-PID-Position-Control
This repo contains PID compute,calibrate and test calibrate routines

Use the functions of this library as per the order in the example code.


**To Do**: -Implement EEPROM functionalities so that the need to recalibrate the motor every time doesnot arries.
       -Replicate the encoder library into this library to write the current encoder position as per our need.

Use serial monitor to test the functions of the library. Make sure to check the CCW and CW rotation of the motor or else the motor might rotate in wrong direction in order to find the never appearing target/setpoint.

Install PID autotuner library by Jackw01 and change the encoder lib by creating an empty constructor as shown in below snippet.
![image](https://user-images.githubusercontent.com/54842967/176380515-fb3791c1-07ee-4884-bac6-ff7b8a2e9ffc.png)



**Refrences:** -@curiores (https://github.com/curiores/ArduinoTutorials/blob/main/SpeedControl/SpeedControl/SpeedControl.ino)
           -@jackw01 (https://github.com/jackw01/arduino-pid-autotuner)
