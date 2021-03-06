# PROJECT 3

## Problem Statement:
To make a small enough bot such that it automatically goes to the centre of the maze without any external control.

## Components:

[Power bank](https://robu.in/product/5v-step-power-module-lithium-battery-charging-protection-board-usb-diy-charger-134n3p/?gclid=EAIaIQobChMInLPWmb646QIVSNiWCh1eAAcAEAYYASABEgLELfD_BwE):
This power bank costs barely anything. It is significantly cheaper as compared to its alternatives. It is really small in size as well, so it also fits under the constraint of size reduction.

[Time of flight sensor](https://learn.adafruit.com/adafruit-vl53l0x-micro-lidar-distance-sensor-breakout/arduino-code):
We need a time of flight sensor as we need to know the distance travelled by the bot and this is crucial in making the bot move on its own to the centre of the maze. The sensor used here is VL53L0X, which costs around 1000 bucks, which I think, is manageable.

[Motor](https://robu.in/product/n20-6v-100rpm-micro-metal-gear-motor-with-encoder/):
This is the choice given in the task itself, which is good because of its amazing advantages. It is rated for 6V, but can comfortable run at 5V, used in Arduino. Also, a wheel can be mounted in its shaft. More importantly, it has encoders, and this helps in tracking position of the bot, to make suitable corrections, if any.

Ultrasonic Sensor: We need an ultrasonic sensor to detect the obstacles (the walls of the maze in this case), so that the bot can turn when it senses something. We can use the popular HC-SR04 sensor for this purpose.

Microcontroller: Since we require our bot to be as small as possible, we should use the Arduino Nano, as there aren't many connections here and the Nano is the smallest microcontroller in the Arduino family currently.

These are the components which I suggest so that the bot is as small as possible, with a lot of features available for it to automatically direct itself to the centre of the maze.
