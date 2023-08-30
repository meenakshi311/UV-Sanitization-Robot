# UV-Sanitization-Robot
Ultraviolet light enabled surface disinfecting robot with the prominent feature being automatic object detection.

# Abstract
The main aim of the project is to make robots disinfect a room or a flat surface using ultraviolet germicidal irradiation. The robot has ultraviolet LEDs which are
responsible for killing the virus. Bio-organisms such as bacteria and viruses are known to be deactivated when exposed to UV light.

# Components used
Arduino Pro Mini (1)
<br>
HC-SR04 Ultrasonic module (3)
<br>
L293D Motor driver (1)
<br>
5Volt N20 motors and mounting brackets (2)
<br>
N20 motor wheels (2)
<br>
UV LEDs (8)
<br>
7805 Voltage Regulator (1)
<br>
7.4V Li-Ion Battery (1)
<br>
330R Resistor (10)
<br>
Dotted Board (1)
<br>
Foam Board or MDF (As per requirement)
<br>
castor wheel (1)
<br>

# Working Principle
● The three ultrasonic sensors that detect the obstacles. As we are using three ultrasonic sensors, we connect all respective Ground and VCC pins, the Ground pin goes to the ground of
the Arduino, and the VCC pin goes to the VCC pin of the Arduino. 
<br>
● Connect trigger and echo pins to Arduino PWM pins, as shown in the circuit diagram. We are using the popular L293D motor driver IC to drive the motors, and connect the two enable pins of the motor driver to 5V, also we need to connect the driver voltage pin to 5V because we are using 5V compatible motors.
<br>
● We have connected all the UV LEDs in parallel each of which contains a current limiting resistor and we tied them all up to VCC and ground. In our case, we choose this resistor according to the LED type we are using, the LEDs are generic type so we are using a 330ohm resistor. The Arduino, Ultrasonic modules, motor driver, and motors work on 5 Volt higher voltage will kill it and we
use a 7.4-volt battery to convert that into 5 Volt, a 7805 voltage regulator is used.

# Circuit Diagram
![image](https://github.com/meenakshi311/UV-Sanitization-Robot/assets/80347426/7cb7fa9b-4253-4792-a125-2f7b4d4d25bb)

# Results
We have seen that while the robot is powered ON, the UV LEDs will stay ON and the
sterilization process will continue. It has a total of ten UV LEDs (Two on each side and two on
the downside)and 3 UV sensors (one on each side) giving a 360°+ downside sterilization. This
robot is 100% safe to operate and it will detect items in the environment for its operation and the
safety of operators (obstacle avoidance). The robot is fully autonomous when UV irradiation is
being performed, this robot has a full 360-degree movement.

