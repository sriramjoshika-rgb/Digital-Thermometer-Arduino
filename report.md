# Digital Thermometer using Arduino

## Objective
To measure ambient temperature using an LM35 sensor interfaced with Arduino Uno.

## Components Used
- Arduino Uno
- LM35 Temperature Sensor
- Breadboard
- Jumper Wires
- USB Cable

## Circuit Connections
LM35 VCC -> Arduino 5V

LM35 GND -> Arduino GND

LM35 OUT -> Arduino A0

## Software
Arduino IDE

## Working
The Arduino reads the analog value from the LM35 sensor, converts it into temperature in Celsius, and displays the result on the Serial Monitor every second.

## Sample Output
Temperature: 27.5 °C

Temperature: 27.8 °C

Temperature: 28.1 °C

## Conclusion
The digital thermometer successfully measures and displays temperature using Arduino.
