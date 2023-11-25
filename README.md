# Autonomous-multipurpose-home-cooling-system
This is a model of a smart cooling system designed with a DHT11 sensor, MQ-2 gas sensor and HC-SR501 PIR motion sensor.

Sensors used: HC-SR501 Passive Infrared (PIR) motion sensor, MQ-2 gas sensor, DHT11 (Digital Humidity and Temperature) sensor.
Actuators used: 12V DC Fan, Liquid Crystal Display (LCD), Light Emitting Diodes (LEDs), Buzzer.
Power source: AC, 12V DC supply. 

The PIR sensor’s sensitivity ranges up to 20 feet (6 meters) 110 ° x 70 ° detection range. 
When the sensor detects high levels of infrared radiation (a human is within its sensitivity range), it gets triggered.
The DHT11 sensor starts taking readings.
The DHT11 sensor measures the ambient temperature and subsequently turns on the DC fan. 
It prints the measured ambient temperature and fan speed on the LCD. 
The fan speed gradually increases as the ambient temperature increases.

Assuming the temperature sensor readings go beyond a certain upper limit (could be a fire or gas leakage), a red LED turns on, indicating danger. “FIRE” is printed on the LCD.
The MQ-2 gas sensor detects methane, butane, hydrogen, Liquefied Petroleum Gas (LPG), smoke and carbon monoxide concentrations in the air, with concentrations ranging from 200 – 10,000 ppm. 
If either of these are detected, the red LED comes on, “GAS LEAKAGE” is printed on the LCD and the buzzer output becomes HIGH, generating a high pitch.
