# Adeept 4WD Smart Car Kit for Raspberry Pi PiCar-B
## DEMO
![Watch Now](https://youtu.be/v5dI3-PlVII)

## About This Product

The Adeept PiCar-B is an educational, smart car robot kit that aims to familiarize customers with sensors,actuators, and data transmission as a facet of the Internet of Things. As a company, Adeept is a “technical service team of open source software and hardware […] Dedicated to applying the Internet and the latest industrial technology in open source area, [and striving] to provide the best hardware support and software service for general makers and electronic enthusiasts around the world.” Currently, the software that comes with the robot kit is similar to that in self-driving cars: Distance–Sensing software, Distance–Maintaining software, Line–Following software, Voice/Speech Recognition and Audio–Processing softwares, and even Object–Tracking software!

## About Adeept

Adeept is a technical service team of open source software and hardware. Dedicated to applying the Internet and the latest industrial technology in open source area, we strive to provide best hardware support and software service for general makers and electronic enthusiasts around the world. We aim to create infinite possibilities with sharing. No matter what field you are in, we can lead you into the electronic world and bring your ideas into reality.

## Contact Info
 Technical Support:  support@adeept.com<br/>
 Customer Service:   service@adeept.com<br/>
 Website:            www.adeept.com<br/>
## Why create a PiCar?
The Adeept PiCar-B is an educational, smart car robot kit that aims to familiarize customers with sensors,actuators, and data transmission as a facet of the Internet of Things. The assembly of the robot was complex and took a lot of time to complete, but the Graphical User Interface of the software included with the PiCar-B Although the PiCar-B comes with its own “hat” for connecting the motor and sensors to the Raspberry Pi’s GPIOs, in the future, I would like to research how to attach more or different sensors to the Pi & PiCar to alter the functionality of the robot. Currently, the software that comes with the robot kit is similar to that in self-driving cars: Distance–Sensing software, Distance–Maintaining software, Line–Following software, Voice/Speech Recognition and Audio–Processing softwares, and even Object–Tracking software!

# PiCar Setup
![screenshot](https://s3.ap-northeast-2.amazonaws.com/storage-u-additor.io/5c9376ce6e1c51000f3498cf/image/0x0/gJQx9mV3pxfQHJGFpGShaEhPS514WkqszBDfPZfG) 
## Features
- STEM Educational Robot - An complete AI(Artificial Intelligence) robot kit based on the Raspberry Pi(Compatible with RPi 3B/3B+/2B/2B+, Raspberry Pi is NOT included).
- Speech Recognition - PiCar-B can be controlled by voice; Object Recognition and Tracking - based on openCV; Automatic Obstacle Avoidance - based on ultrasonic sensor; Line Tracking - based on infrared reflection; C/S Architecture - can be remotely controlled by APP on PC; WS2812 RGB LEDs - can change a variety of colors, full of technology; Real-time Video Transmission.
- Powered by 2x 18650 batteries.

## Provided Contents
- 1 Set Acrylic Plates
- 1x Adeept Motor HAT V2.0
- 1x Raspberry Pi Camera(with Cable)
- 1x USB Microphone
- 1x Ultrasonic Sensor Module
- 2x Adeept RGB LED Module
- 4x Adeept WS2812 RGB LED Module
- 1x Adeept 3CH Line Tracking Module
- 3x Servo
- 1x Gear Motor
- 4x Wheels
- 1x Battery Holder
- 1x Cross Socket Wrench
- 2x Cross Screwdriver(Small and Large)
- 1x Winding Pipe
- 10x Bearing(6*F624ZZ + 4*F687ZZ)
- 2x Umbrella Gear Set

## Assembly
- Identified, Labeled, and Sorted the nuts, screws, spacers, bearings, sensors, servos, and acrylic frame pieces. ( which each had paper covers that had to be removed; a tedious extra step! ) 
- Assembled the acrylic frame pieces with the provided screws and nuts. 
- Attached battery holder and RGB LED under-lights. 
- Attached/Connected the PiCar’s motor, umbrella gear, rear axle, and rear wheels. 
- Calibrated the front wheel servos.
- Built the the front frame and and mounting the servos that turn the front wheels.
- Connected the front and back ends and adding in the slick RBG LED “Headlights” that indicate the PiCar-B’s Status.
- Assembled the “Transformer head” with the Ultrasonic Ranging Module, Camera, and servos with rocker arms that turn the head up and down and the “neck” left and right. 
- Mounting the Head to the front of the acrylic frame. 
- Mounted the Sensor Hat to the Raspberry Pi with spacers and screws.
- Mounted the Raspberry Pi / Sensor Hat Combo to the acrylic frame.
- Plugged in the USB Voice Module to the Raspberry Pi.
- Connected the sensors, servos, LEDs, and Put the Batteries in. 

## Summary and Surprises
There are many instances in the manual where the description of a software or install command is disorganized and located far away from the actual number, bullet, or paragraph where the text should be located. The text in the Software part of the manual is clumped together and has no concept of using line spacing or white space to make text more readable. We found ourselves frequently losing our position in the manual, frantically scrolling back and forth to attempt to find what we were looking for.
Although the PiCar-B comes with its own “hat” for connecting the motor and sensors to the Raspberry Pi’s GPIOs, in the future, I would like to research how to attach more or different sensors to the Pi & PiCar to alter the functionality of the robot.

We ran into many problems and time constraints building and programming the robot, but once assembled, the Graphical User Interface of the software included with the PiCar-B made it relatively easy to see the direct results of the code, sensors, and user commands. Our testing methods for the PiCar, once we were done assembling and downloading, consisted primarily of using the manual’s GUI pictures to determine what the client.py program should be displaying versus what it is actually displaying.

In general, the pictures, specifically in the Assembly and Testing/Running sections of the manual, were much better at communicating the author’s intent and instructions than whatever Google-Translated English text the authors inexplicably got paid to write. 

Another problem we ran into was the PiCar turning left but not right. We could see each of the Keyboard Controls/Shortcuts worked triggering in the GUI, but when we pressed Right, the PiCar’s wheels would not turn past 90 degrees (straight ahead of the robot). We determined that the front wheels did not have the correct range of motion because the servo somehow got incorrectly calibrated. It took an incredible amount of time, effort, and questioning the existence of God to be able to disassemble the robot, recalibrate the servos, and finally put it all back together.

In addition, the manual itself is written for users with a Windows computer, which made it extremely difficult to install the necessary software on our Macbook. What seemed at first like easy-to-follow directions became nightmarishly difficult on the Mac!

## LED Sensors
![LED Sensor](https://s3.ap-northeast-2.amazonaws.com/storage-u-additor.io/5c9376ce6e1c51000f3498cf/image/0x0/t1FSgd5SVjFD3iVimyoCuUGHBO6JJ8Fhg1xHYO3b)
