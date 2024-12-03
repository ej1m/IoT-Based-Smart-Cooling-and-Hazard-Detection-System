# Smart cooling and hazard detecton system
This project involves the design and implementation of a smart cooling and hazard detection system that integrates environmental monitoring and automated responses for enhanced functionality.

Sensors Utilized:

•	HC-SR501 PIR Motion Sensor: Detects motion within a sensitivity range of up to 6 meters and a 110° x 70° field of view. It is triggered by infrared radiation, such as the presence of a human within its range.

•	DHT11 Temperature and Humidity Sensor: Measures ambient temperature and humidity.

•	MQ-2 Gas Sensor: Monitors air quality, detecting gases such as methane, butane, hydrogen, liquefied petroleum gas (LPG), smoke, and carbon monoxide in concentrations ranging from 200 to 10,000 ppm.

Actuators Utilized:

•	12V DC Fan: Adjusts speed based on temperature readings.

•	Liquid Crystal Display (LCD): Displays temperature, fan speed, and alerts.

•	Light Emitting Diodes (LEDs): Provides visual indicators for system states.

•	Buzzer: Generates audible alerts during emergency conditions.

System Operation:

When the PIR motion sensor detects a humans’ presence within its range, the DHT11 sensor activates to measure ambient temperature. Based on the temperature readings, the DC fan is turned on, and its speed is adjusted proportionally to the temperature increase. The ambient temperature and fan speed are displayed on the LCD.

In scenarios where the temperature exceeds a predefined upper limit, indicating a potential fire or other hazard, a red LED illuminates, and "FIRE" is displayed on the LCD. Concurrently, the MQ-2 gas sensor monitors the environment for harmful gases or smoke. Upon detecting dangerous levels, the red LED and buzzer activate, while "GAS LEAKAGE" is displayed on the LCD to alert users to the hazard.

Power Supply: The system is powered by a 12V DC supply and can also utilize AC power.

This system effectively combines environmental monitoring, safety, and automated cooling, making it suitable for applications requiring enhanced safety and comfort.
