## Portable RPM Meter using IoT / C++.
This repository contains the source code of the sketch named RPM_sketch.ino

## Abstract
Digital Tachometer using an IR Sensor with the help of Arduino for measuring the number of rotations of the rotating Motor in RPM. Here we have interfaced the IR sensor module with Arduino and the 0.96-inch OLED display to display the RPM count. The IR sensor module consists of an IR Transmitter and receiver that can work as a Digital Tachometer for speed measurement of any rotating object. There are two types of tachometers one is mechanical and another one is digital. Here we are going to build an Arduino-based digital tachometer using an IR sensor module.

## Introduction
The Tachometer is an RPM counter used to measure the number of rotations per minute. The unit of measurement of the tachometer is the revolutions per minute (RPM). So, in short, we can say that a tachometer is an instrument that measures RPM.
Measurement of speed is necessary to know whether the motor is running at rated speed or not. Generally, we use a tachometer to measure the speed of rotating objects like a motor, fans, and automobiles to reduce human effort without direct contact with the motor, and to make the measurement of speed easy we have used a digital tachometer using Arduino Pro mini. 
The first mechanical tachometers were based on measuring the centrifugal force, similar to the operation of a centrifugal governor.  To construct a simple digital RPM meter, we need to work in three different fields. 
To meet these requirements, we use a digital tachometer using Arduino. In the hardware section, we design a comparator circuit to take the inputs using Arduino & through the software section we control the Arduino, calculations, and outputs. The transmitter section includes an IR sensor, which transmits continuous IR rays to be received by an IR receiver module.  
An IR output terminal of the receiver varies depending upon its receiving of IR rays. Since this variation cannot be analyzed as such, this output can be fed to a comparator circuit. Here an operational amplifier (op-amp) of LM 339 is used as a comparator circuit.

## Glimpse of project

![image](https://github.com/nobody1804/IoT_source_for_RPM_meter/assets/97802204/0e0d6d53-7a06-4921-8284-2f19d2c85d17)

## Circuit Diagram

![image](https://github.com/nobody1804/IoT_source_for_RPM_meter/assets/97802204/e5f0f524-3233-4f7f-85c2-974804463455)

## Conclusion

The Digital Tachometer uses an IR Sensor that displays the RPM to the driver as well as shows the driver when to change gear using the LED lights. The RPM was displayed on the computer rather than an LCD screen due to the connections made on the Arduino Uno. The LCD screen could not be connected to the board as the digital pins were already used for the demultiplexer chip.

