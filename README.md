Solar-Driven Semi-Autonomous Eco-Friendly Grass Cutter

Introduction
This project presents a Solar Powered Grass Cutter with Semi-Automated and Bluetooth Control functionality, designed for smart and sustainable lawn maintenance. The system operates using solar energy, reducing dependency on conventional power sources. It features a semi-automated cutting mechanism that can be remotely controlled via a smartphone using Bluetooth, allowing users to manually guide or stop the cutter when needed. This dual-mode operation makes it ideal for small to medium-sized lawns where energy efficiency, user convenience, and eco-friendliness are priorities. The design combines clean energy usage with practical automation to promote green technology in everyday applications. [Picture](https://github.com/user-attachments/assets/e7753b9c-c03b-479a-b297-dc8ad538b899)


Features

*Solar Powered Operation – Utilizes solar energy, reducing electricity costs and promoting eco-friendly usage.

*Semi-Automated Cutting – Operates autonomously in predefined areas while allowing manual intervention.

*Bluetooth Control – Enables remote control via smartphone for start/stop and directional movement.

*Rechargeable Battery – Stores solar energy for continuous operation during cloudy weather or at night.

*Compact and Portable Design – Lightweight and easy to move, suitable for small to medium lawns.

*Safety Features – Includes emergency stop and obstacle detection to prevent accidents and ensure user safety.


![Final Circuit](https://github.com/user-attachments/assets/6359fb5b-571a-4139-846b-1984f72e9d80)


Components Used

•	Arduino Nano (Microcontroller)

•	L298N Motor Driver (For vehicle motor control)

•	6 DC Motors (For movement)

•	BLDC Grass Cutting Motor (Controlled via a relay module)

•	1-Channel Relay Module (For grass-cutting motor control)

•	Ultrasonic Sensor (HC-SR04) (For obstacle detection)

•	Servo Motor (For directional adjustments)

•	HC-05 Bluetooth Module (For wireless control)

•	12V, 10W Solar Panel (For renewable energy supply)

•	11.1V Li-Ion Battery (For energy storage)

•	Mode Control Switch (To switch between manual and autonomous modes)

•	Wires & Connectors (For electrical connections)

System Overview

The Solar Powered Grass Cutter system integrates a solar panel to charge a battery, which powers the motor driving the cutting blades. The movement is controlled using a motor driver and wheels, enabling semi-automated navigation. A Bluetooth module allows wireless control via a smartphone app, enabling manual operation when needed. The system combines clean energy, efficient cutting, and user-friendly control for smart lawn maintenance.![App_Interface](https://github.com/user-attachments/assets/486e430a-3c3d-4a50-a04b-f2a0b582e7c8)


Creating the Mobile App Using MIT App Inventor
1.	Open MIT App Inventor – Go to MIT App Inventor and create a new project.
2.	Design the User Interface – Add buttons for movement controls (Forward, Backward, Left, Right, Stop), a Bluetooth connection module, and a status display.
3.	Connect to Bluetooth Module – Use the BluetoothClient component to establish a connection with the HC-05 module.
4.	Send Commands to Arduino – Assign each button to send movement commands via Bluetooth (e.g., "F" for forward, "B" for backward).
5.	Test and Deploy – Install the app on your Android device, pair it with the Bluetooth module, and control the grass cutter remotely.




Applications

*Residential Lawn Maintenance – Ideal for homeowners to maintain small to medium-sized gardens efficiently and eco-friendly.

*Parks and Public Gardens – Helps in maintaining public green spaces with minimal human intervention and zero fuel cost.

*Golf Courses – Suitable for trimming grass in golf courses while reducing energy consumption and noise pollution.

*Agricultural Fields – Can be used for clearing grass and weeds around crops without relying on fuel-powered machines.

*Eco-Friendly Landscaping Services – Perfect for landscaping businesses focused on sustainable and green technology solutions.

