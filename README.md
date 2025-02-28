# Smart-Home-System--Arduino
Design, build, and program a smart home automation and security system using Tinkercad, Arduino IDE, and the IoT Tech Core Kit.

System Functionality:
Door Security: Implement a door sensor to detect and report whether the door is open or closed.
Intrusion Detection: Utilize a distance sensor to monitor for potential intruders within the home.
Automated Lighting: Configure lights to automatically turn on when ambient light levels are low.
Optional Enhancements:
Integrate a water level sensor to detect potential flooding.
Incorporate a temperature and humidity sensor to monitor environmental conditions.

Development Process:
Prototype Design (Tinkercad): Create a virtual representation of the smart home system, including all sensors, actuators, and the microcontroller.
Hardware Implementation (IoT Tech Core Kit): Build the physical system based on the Tinkercad prototype, using the components from the IoT Tech Core Kit.
Software Development (Arduino IDE): Program the microcontroller to control the sensors, actuators, and implement the desired system functionality.

Door Sensor
1)	Green LED to indicate no security issue
2)	Yellow LED and red LED to indicate security issues and to scare off intruder. 
3)	Active Buzzer to sound alarm to scare off intruder
4)	Blue Wire to emulate home entrance door

Referencing the circuit schematic below, connect one end of the blue wire to pin 9 on Arduino Mega Board and the other end to the ground (-) rail of the breadboard. When the wire is connected, it emulates a closed door. This will activate the green LED to turn on and indicates that the home is secure and safe. If the blue wire is removed (i.e. disconnected) from the breadboard while the code is running, then it will emulate an open door. This will activate the flashing red and yellow lights and the buzzer to sound. 

![image](https://github.com/user-attachments/assets/98457e3e-17dc-4b1b-a55b-33342a377289)

Cicuit Door Closed
![image](https://github.com/user-attachments/assets/b6add500-967f-46c0-aed4-dc01a0e447e8)

Circuit Door Open
![image](https://github.com/user-attachments/assets/c6d7d386-7c26-46df-aaa4-3e7ad33f3ea1)
