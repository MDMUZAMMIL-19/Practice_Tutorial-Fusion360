Gas Sensor Robot

Overview

This project is a gas sensor robot designed to detect gas leaks and respond accordingly. The robot is built using the following components: an ESP8266, a charger module, a battery, an LM293D motor driver, 4 geared motors, an MQ2 gas sensor, and a buzzer. The robot is capable of detecting gas presence, alerting via the buzzer, and can be programmed to move to a safer location if necessary.

## Components

- ESP8266: Microcontroller unit for processing and control.
- Charger Module: Used to charge the battery.
- Battery: Powers the robot.
- LM293D Motor Driver: Controls the geared motors.
- 4 Geared Motors: Provide movement for the robot.
- MQ2 Gas Sensor: Detects the presence of gas.
- Buzzer: Alerts when gas is detected.

## Wiring Diagram

1. ESP8266 to LM293D Motor Driver:
   - Connect GPIO pins of the ESP8266 to the input pins of the LM293D.
   - Connect the output pins of the LM293D to the 4 geared motors.

2. ESP8266 to MQ2 Gas Sensor:
   - Connect the analog output of the MQ2 to an analog input pin on the ESP8266.

3. ESP8266 to Buzzer:
   - Connect a digital output pin from the ESP8266 to the buzzer.

4. Power Supply:
   - Connect the battery to the charger module.
   - Connect the output of the charger module to power the ESP8266 and the LM293D motor driver.


## Usage

1. Power On:
   - Ensure the battery is charged and connected.
   - Power on the robot.

2. Gas Detection:
   - The MQ2 gas sensor continuously monitors for gas presence.
   - When gas is detected, the buzzer will sound an alarm.
   - The robot will move to a predefined safe location.


## Future Improvements

- Integrate additional sensors for more comprehensive environmental monitoring.
- Implement Wi-Fi capabilities to send alerts remotely.
- Enhance movement algorithms for more efficient navigation.

## License

This project is licensed under the MIT License. Feel free to modify and distribute as needed.