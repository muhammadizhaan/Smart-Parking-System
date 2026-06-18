🚀 Overview
Finding a parking spot in urban areas can be time-consuming and inefficient. This project solves that problem by using an Arduino-based embedded system equipped with sensors to monitor parking slot availability in real time. The system automates entry/exit gates and displays live slot availability to users before they enter.

Key Features
Real-Time Slot Monitoring: InfraRed (IR) / Ultrasonic sensors detect the presence of a vehicle in each slot.

Automated Gate Control: Servo motors automatically operate the entry and exit barriers upon vehicle detection.

Live Status Display: An LCD screen at the entrance displays the number of available slots in real time.

Intelligent Counting: Prevents entry when the parking lot is completely full.

🛠️ Hardware Requirements
To replicate or build this project, you will need the following components:

Microcontroller: Arduino Uno (or Arduino Mega)

Sensors: * IR Sensors or Ultrasonic Sensors (for individual slot detection)

IR Sensors (for Entry/Exit gate detection)

Actuators: SG90 Servo Motors (for gate barriers)

Display: 16x2 LCD Display (with I2C module for cleaner wiring)

Miscellaneous: Jumper wires, Breadboard, 10k Ohm resistors, External power supply (if required for multiple servos).

💻 Circuit Diagram & Pin Mapping
Note: Customize the pin mapping below according to your exact hardware connections.

Component	Arduino Pin	Description
IR Sensor (Entry)	Pin 2	Detects incoming vehicle
IR Sensor (Exit)	Pin 3	Detects outgoing vehicle
Servo Motor (Entry)	Pin 5	Controls entry gate
Servo Motor (Exit)	Pin 6	Controls exit gate
I2C LCD SDA	Pin A4	Data line for display
I2C LCD SCL	Pin A5	Clock line for display
Slot 1 Sensor	Pin 7	Monitors Parking Slot 1
Slot 2 Sensor	Pin 8	Monitors Parking Slot 2
