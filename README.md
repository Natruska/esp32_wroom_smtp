ESP32 WROOM - Send Email on Button Press. 
This project uses the ESP32 WROOM microcontroller to send an email when a button is pressed. The ESP32 connects to a WiFi network and uses an SMTP server to send the message.

Features
1. Connects to WiFi
2. Synchronizes time from an NTP server
3. Detects button press
4. Sends an email to a specified address

Hardware Requirements
(ESP32 WROOM)
(4-pin push button)
(Pull-down resistor (e.g., 10kΩ)

Setup Instructions
1. Configure WiFi credentials and SMTP server settings in the code.
2. Connect the button to ESP32, e.g., D12 pin and GND.
3. Upload the code to ESP32 and power it on.
4. Press the button to send an email.

Possible Expansions
This project can be expanded by replacing the button with a motion sensor or another type of sensor. This way, ESP32 can automatically send an email when movement is detected.
