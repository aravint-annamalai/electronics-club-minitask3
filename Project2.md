# PROJECT 2

## Problem Statement:
Here, an 18 DOF hexapod is to be implemented using Reinforcement Learning. In RL, it is important to know the state of the bot and we have to recreate it in the computer. So, this is what we want to achieve.

## Pipeline:
Movement of the bot => Captured by IMU sensors => Processed by using Arduino and feeding it to AutoCAD software => The AutoCAD software now contains the orientation of the bot.

## Sensor:
We have to use an IMU sensor so that it captures the movement of the bot and sends data. I suggest to use MPU6050 IMU sensor(which has 6DOF, 3 axes for accelerometer and 3 axes for gyroscope). If we want more sophistication, then we can use MPU9150 which is the same as MPU6050, but with an extra magnetometer attached.

Here is a [tutorial](https://maker.pro/arduino/tutorial/how-to-interface-arduino-and-the-mpu-6050-sensor) to interface the MPU6050 sensor with Arduino.

### Advantages:
As said in the tutorial link above, the MPU 6050 sensor is comparatively cheaper than its alternatives, so the budget constraint is met. 
Also, it performs better, so it is a win-win situation in terms of budget optimization and performance enhancement.

