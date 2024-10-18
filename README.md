IMPORTANT THINGS TO CONSIDER

  The required libraries (ESP8266WiFi.h, BlynkSimpleEsp8266.h) installed.
  Correct wiring between NodeMCU and Arduino Mega for serial communication.
  Extract the .hex file(Binary Code) from arduino and nodemcu first in order to revert the changes made in case an error occurred.

Wiring changes:

NodeMCU GPIO1 (TX) → Arduino Mega RX1 (Pin 19);
NodeMCU GPIO3 (RX) → Arduino Mega TX1 (Pin 18)

Arduino Mega (Pin 2) → Relay(IN1);
Arduino Mega (Pin 3) → Relay(IN2);
Arduino Mega (Pin 4) → Relay(IN3);
Arduino Mega (Pin 5) → Relay(IN4);
