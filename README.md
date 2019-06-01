# group-07
## What?
We aim to create a remote controlled car emphasizing on hassle-free use and automation. 

## Features 

### Obstacle detection and manoeuvring
* Alert for detection of obstacle
* Automatic braking upon detecting obstacle 
* Drive around obstacle when detected

### Mobility
* Forward
* Reverse
* Stop
* Turn left and right

### Sportmode 
**SPORTMODE ACTIVATED**
* Speed is set to maximum speed instantly
* Speed is decreased instantly meaning instant braking

**SPORTMODE DEACTIVATED**
* Speed is increased or decreased gradually 
* Does not reach maximum speed

### Cruise control
* Static Cruise Control. User can set a defined speed
* Adaptive Cruise Control. Adapts the speed to the object infront of it

### Tilt control 
* Turning left or right by tilting the phone 

### Autopilot driving 
* Car will be able to drive on and follow a single line

### Tail lamps and head lamps
* Tail lamps will turn on upon braking
* The user will be able to toggle the head lamps on and off

## Why?
Our product has several functionalities. Each feature has a purpose that can solve a real world problem. 
We think if we are able to understand and make these features work on a smaller scale then we can lay out the blueprint for how it should be programmed for real vehicle use. By using a small Smart car we can test out the features and check for any problems that may occur in real scenarios. 


## How?
We used android studio to make an application where we can remotely control the car. The app has butttons that can turn on a feature of the car when needed. The app is connected to the car via the bluetooth on the arduino. 

We also used the Arduino IDE and the Smart Car shield library to program the features needed. 

The features are of course dependant on the hardware we are using. We were using these for the features: 
* Obstacle detection and manoeuvring were made by using ultrasonic sensor
* Mobility was implemented through the smartcar library and the gyroscope
* Cruise control was managed by an ultrasonic sensor
* Tilt Control was be managed by the gyroscope in the users mobile device
* Autopilot was managed by the infrared sensor 

## Hardware Used
- Arduino MEGA 2560
- SmartCar
- 5x Ultrasonic sensors 
- 1x IR Sensor 
- 3x Breadboards
- Battery Pack(4 batteries)
- Bluetooth HC-06
- 4x DC motors
- Gyroscope
- 2x Odometers
- Android Smartphone (running Android 9.0 or later) 
- USB A-B Cable
- Surge protector 

## Software used
- Arduino IDE
- Android Studio
- Visual Paradigm (Software architecture)

## Project Developers  
- Lema Rassul
- Talha Hussain
- Haider Ali
- Osman Osman
- Mujahid Khan
- Ali Aziz
