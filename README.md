# Team-NextGen
This repository showcases the work and innovations of Team NextGen in the WRO Future Engineers category.
## Introduction
Team Next-Gen is thrilled to make our debut at the World Robot Olympiad (WRO), marking our very first participation in this prestigious global competition. It has been a blessing and an incredible learning journey to design and build our self-automated car from the ground up, making it run successfully during our very first trial.  
With dedication, teamwork, and countless hours of effort, we continually refined and upgraded the bot through multiple versions to reach its present form. Each iteration pushed us to learn more, innovate further, and overcome new challenges—strengthening both our technical expertise and our problem-solving mindset.This documentation provides a detailed overview of our bot’s design, development process, and functionality. From mobility and power management to sensor integration and navigation strategies, every component reflects our commitment to doing our best in our very first Olympiad.  
As Team Next-Gen, we are excited to showcase not just our hard work, but also our passion for robotics, and we look forward to further improving and advancing our car in the journey ahead.

## Team Members
### Coach's name: Tahmidur Rahman Swad 
- Fahim Faisal  
- Nabiha Tahsin Ruhama  
- Rabaya Akter Roshny  

## Table of contents 
- Team Photo  
- Bot Photo  
- Schematics  
- 3D Models  
- Vehicle Code  
  - Open Challenge   
  - Obstacle Challenge  
- Videos  
## Bot description 
* `CAMERA (DFrobot Huskylens AI camera)`    Why we used it: The WRO Future Engineers challenge requires the car to recognize lanes, signs, and obstacles in real time. The camera provides continuous image data, which we process with computer vision algorithms to keep the car on track and make decisions.
* `Ultrasonic sensor (HC-SR04)`   While the camera handles vision, sonar ensures the car can measure distance to walls or barriers, helping with safe navigation and parking accuracy.
* `Microcontroller( ESP32)`    It processes sensor data, runs control algorithms, and sends commands to motors and actuators. The ESP32 is small, lightweight, and powerful enough to handle real-time operations for a self-driving car.
* `Servo motor  (SG90)`     Controls the steering mechanism. Servos are ideal for steering because they can rotate to exact angles, allowing the car to follow curves smoothly and make controlled turns in the narrow lanes of the WRO track.
* `Gyro sensor (MPU9250)`   Used for checking and counting turns so that the bot stops after completing three laps and also used in parking as it measures rotation angles.
* `Motor driver`   Controls the motor’s speed and direction.
