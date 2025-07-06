# Line Follower Robot with Obstacle Avoidance and Bluetooth Control

## Overview

This project showcases a multi-functional **line follower robot** developed as part of the *IC 152: Makerspace Laboratory* course. The robot is designed to autonomously navigate a path using infrared sensors, detect and avoid obstacles using an ultrasonic sensor, and receive commands via a mobile app using Bluetooth communication.

---

## Team

**Batch:** B1  
**Team:** H  

| Name              | Roll No.   |
|-------------------|------------|
| Pathak Krish      | 230002049  |
| Mudit Tiwari      | 230002044  |
| Nishit            | 230002047  |
| Nitin Mewara      | 230002048  |
| Pranav            | 230002045  |
| Naman Goyal       | 230002046  |

---

## Features

- Autonomous line-following using IR sensors  
- Real-time obstacle detection and avoidance using ultrasonic sensor  
- Bluetooth-based remote control via mobile app  
- Custom-built chassis with 3D-printed wheels  

---

## Components Used

- Arduino Uno Microcontroller  
- IR Sensors (x2)  
- Ultrasonic Sensor (HC-SR04)  
- L298N Motor Driver  
- Gear Motors (x4)  
- Servo Motor  
- HC-05 Bluetooth Module  
- Lithium Batteries + Holder  
- Jumper Wires  
- Breadboard  
- 3D-Printed Wheels  
- Acrylic Chassis (Laser Cut)  

---

## System Design

### Line Following

IR sensors detect the black line and guide the robot’s direction by controlling the speed of the motors. Left/right turns are handled by varying motor speeds on each side.

### Obstacle Avoidance

The HC-SR04 ultrasonic sensor measures distance in front of the robot. If an object is detected within 15 cm, the robot halts and reroutes to avoid it, then resumes line-following.

### Bluetooth Control

A mobile phone app connects via the HC-05 Bluetooth module to allow remote operation, enabling control over direction and speed with predefined commands.

---


## Key Learnings

- Gained hands-on experience with Arduino programming and sensor integration  
- Learned the importance of mechanical design in robot performance  
- Understood motor control and sensor feedback mechanisms  
- Practiced circuit wiring and real-time debugging  
- Strengthened collaborative and team-based project development skills  

---

## How to Use

1. Power the robot using lithium-ion batteries.  
2. Upload the Arduino sketch to the board using the Arduino IDE.  
3. Place the robot on a surface with a black line.  
4. The robot will follow the line autonomously.  
5. Introduce obstacles to observe avoidance behavior.  
6. Connect a mobile phone via Bluetooth for manual control if needed.  

## Photos

```markdown
![Robot Front View](your_image_path/front_view.jpg)
![Robot Side View](your_image_path/side_view.jpg)

---

