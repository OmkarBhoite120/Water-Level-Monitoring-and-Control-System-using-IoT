# Water-Level-Monitoring-and-Control-System-using-IoT
My FYMSc(CS) mini-project for First sem. An automated system using ESP32 and ultrasonic sensor to monitor water levels and control a pump. It sends real-time data via Wi-Fi, refills when low, and stops when full—reducing manual work and water wastage.


## Introduction :
Effective management of water resources is essential to full fill daily needs while minimizing
wastage. A common challenge in water management involves maintaining optimal levels in
storage systems like tanks and reservoirs. Fluctuations in water levels often demand constant
monitoring and manual interventions, which can be inefficient and prone to errors.
The advent of Internet of Things (IoT) technology has revolutionized water management by
enabling remote and real-time monitoring of water levels. This project aims to create an
automated system for monitoring and controlling water levels using IoT, reducing the need for
manual oversight and enhancing efficiency. By integrating the ESP32 microcontroller and the
JSN-SR04T ultrasonic sensor, the system measures water levels precisely and transmits the data
to an IoT platform. The ESP32’s Wi-Fi capabilities facilitate seamless data communication,
while the ultrasonic sensor measures the distance to the water surface, allowing accurate
determination of water levels.
Based on these measurements, the system activates a relay to control a water pump or valve,
maintaining the desired level automatically. For instance, if the water level drops below a set
threshold, the system can trigger a buzzer or activate the pump to refill the tank. Similarly, it can
prevent overflow by switching off the pump or sounding an alert when the maximum level is
reached.

## Objective :
1. Accurate Measurement
Utilize the JSN-SR04T ultrasonic sensor to measure the water level by calculating the
distance to the surface accurately.
2. Automated Pump Control
Automate the pump’s operation by activating it when water levels are low and
deactivating it when the maximum threshold is reached, preventing both overflow and
dry running.
3. Real-Time Monitoring
Transmit water level data wirelessly via the ESP32 to an IoT platform like Blynk,
enabling users to monitor levels remotely.
4. Alerts and Notifications
Provide timely alerts for critical water levels, ensuring prompt action.
5. Resource Optimization
Minimize water and energy wastage by optimizing pump operations.
6. User-Friendly Interface
Develop a simple and intuitive interface for users to monitor, control, and receive
notifications.
7. Cost-Effective Implementation
Use affordable, readily available components to make the system accessible for
widespread applications.

## Methodology:


<img width="505" height="980" alt="image" src="https://github.com/user-attachments/assets/cab17eb3-4e51-4f40-9ff7-3b4bb0b21350" />

1. Requirement Analysis
Identify the required hardware components, such as the ESP32 and JSN-SR04T, and
research suitable IoT platforms for data communication.
2. Component Procurement
Acquire the necessary hardware, including sensors, controllers, and other peripherals.
3. Circuit Design
Develop and test the circuit, connecting the ESP32, ultrasonic sensor, and relay module.
4. Software Development
Write firmware for the ESP32 to handle water level measurements, pump control, and
integration with the IoT platform.
5. Integration and Testing
Assemble hardware and software, test the system under varying conditions, and calibrate
for accuracy.
6. Optimization
Refine sensor calibration, improve software for energy efficiency, and fine-tune IoT
configurations.
7. Final Testing and Validation
Test the system in real-world scenarios to ensure accuracy, reliability, and
responsiveness.
8. Deployment and Improvements
Deploy the system and gather feedback for future upgrades, such as adding additional
sensors or advanced analytics.

## Applications and Benefits
### Software Requirements
1. Programming Environment
Arduino IDE: A user-friendly platform for coding and uploading programs to the ESP32,
supporting various libraries for seamless hardware and IoT integration.
2. Libraries
Ultrasonic Sensor Library: Enables accurate distance measurement using the JSN-SR04T
sensor.
Wi-Fi Library: Facilitates wireless communication between the ESP32 and IoT
platforms.
Blynk Library: Integrates the ESP32 with the Blynk IoT platform for monitoring, control,
and data visualization.
3. IoT Platform
Blynk: A cloud-based IoT solution for real-time monitoring and alert generation.
4. Code Deployment Tools
ESP32 Toolchain: Used for compiling and uploading code to the ESP32 microcontroller.
### Hardware Requirements
1. Microcontroller
ESP32 Development Board: Central to the system, providing processing capabilities and
Wi-Fi connectivity.
2. Sensor
JSN-SR04T Ultrasonic Sensor: Measures the water level by determining the distance to
the water surface.
3. Connectivity Tools
Jumper Wires: Ensure secure connections between components.
Breadboard: Useful for prototyping and testing.
4. Enclosure
Waterproof Housing: Protects components from environmental factors, ensuring
durability and reliability.

## COMPONENTS :
### ESP-32 :

<img width="652" height="569" alt="image" src="https://github.com/user-attachments/assets/93e7aa53-006f-48a8-af31-a79add41ef93" />

### JSN-SR04T :

<img width="635" height="369" alt="image" src="https://github.com/user-attachments/assets/4a33515c-6f2b-407d-a35d-af734f9f1108" />


### GUI INTERFACE :
<img width="1006" height="622" alt="image" src="https://github.com/user-attachments/assets/817225a1-a21f-4b29-ae7f-c6c2d18b9320" />
