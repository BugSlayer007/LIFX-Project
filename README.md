This Arduino project demonstrates how to use UDP (User Datagram Protocol) and WiFi to control an LED. When a UDP packet is received, the LED turns red. The project is designed to be flexible, allowing the WiFi SSID and LED pin to be configured in separate header files for easy modification.

Prerequisites
Before you start, ensure you have the following:

An Arduino board with WiFi capabilities (e.g., Arduino Uno WiFi Rev2, ESP8266, ESP32).
An LED and a suitable resistor.
Arduino IDE installed on your computer.
Hardware Setup
Connect the LED to the specified pin on your Arduino board (as defined in led_pin_file.h).
Connect the other end of the LED to a resistor, and then to the ground (GND) pin on the Arduino board.



Future Improvements
Implement different colors or patterns based on the content of the UDP packet.
Add error handling and connection status checks.
Optimize the delay mechanism to make the LED response more responsive to incoming packets.



