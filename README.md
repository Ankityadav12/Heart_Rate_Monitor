# Heart_Rate_Monitor
In this project, we used an Arduino board and a heartbeat sensor to create a heart rate monitor system. Using a useful heartbeat sensor, you may learn how the heartbeat sensor operates and how an Arduino-based heart rate monitoring system works.


The heart rate, or pace of the heartbeat, is measured using a device called a heartbeat sensor. The fundamental actions we do to maintain our health include checking our body's temperature, heart rate, and blood pressure.

We use thermometers to gauge body temperature and a sphygmomanometer to track blood pressure or arterial pressure.

There are two ways to check your heart rate: manually by feeling your wrists or neck for a pulse, or by using a heartbeat sensor.


Introduction to Heartbeat Sensor

For patients and sportsmen, monitoring heart rate is crucial since it reveals information on the health of the heart (just heart rate). Heart rate can be measured in a variety of methods, but electrocardiography is the most accurate.

But using a Heartbeat Sensor is a simpler approach to keep track of heart rate. It gives you an immediate approach to measure the heartbeat and comes in a variety of sizes and shapes.

Chest straps, smart phones, wrist watches (smart watches), and other devices all have heartbeat sensors. The number of times the heart contracts or expands in a minute is expressed in terms of beats per minute, or bpm. 



Components Required
Arduino UNO x 1 
16 x 2 LCD Display x 1 
10KΩ Potentiometer 
330Ω Resistor (Optional – for LCD backlight) 
Push Button 
Heartbeat Sensor Module with Probe (finger based) 
Mini Breadboard 
Connecting Wires 


Circuit Design of Interfacing Heartbeat Sensor with Arduino

The circuit design of Arduino based Heart rate monitor system using Heart beat Sensor is very simple. First, in order to display the heartbeat readings in bpm, we have to connect a 16×2 LCD Display to the Arduino UNO.

The 4 data pins of the LCD Module (D4, D5, D6 and D7) are connected to Pins 1, 1, 1 and 1 of the Arduino UNO. Also, a 10KΩ Potentiometer is connected to Pin 3 of LCD (contrast adjust pin). The RS and E (Pins 3 and 5) of the LCD are connected to Pins 1 and 1 of the Arduino UNO.

Next, connect the output of the Heartbeat Sensor Module to the Analog Input Pin (Pin 1) of Arduino. 
